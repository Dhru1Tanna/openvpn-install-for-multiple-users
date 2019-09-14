# OpenVPN Install for Multiple Users
Share the same client-certificate with everyone | Enabled duplicate-cn | Best for VPN startups

## Installation
Run the script
```
wget https://git.io/JeYgM -O openvpn-install.sh && bash openvpn-install.sh
```

## Remove
* Uninstall OpenVPN
```
sudo apt remove openvpn
```

* Remove it's dependencies
```
sudo rm -rfv /etc/openvpn
```
