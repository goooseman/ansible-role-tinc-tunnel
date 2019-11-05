# Tinc Tunnel

Do you have a device, which does not have a direct IP address and/or behind a Firewall, but you want to connect to any of its' port (e.g. to open a website hosted on the device or to connect using SSH/mosh)? Use this playbook to set up a [Tinc VPN](https://www.tinc-vpn.org/) connection between your device and a proxy server (direct IP address is a must for this proxy server).

> Set-ups Tinc VPN, HTTP (with Let's Encrypt's HTTPS) proxy, TCP and UDP proxy on a cloud server, set-ups tinc VPN on a target server.

Based on [ansible-role-tincvpn](https://github.com/MatthiasLohr/ansible-role-tincvpn) and [a blog article from Jordan Crawford](https://jordancrawford.kiwi/home-server-without-portforward/).