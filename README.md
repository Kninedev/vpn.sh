vpn.sh
======

Script to setup IPSec/L2TP VPN. 

Tested on Ubuntu 14.04. Connected clients use Google DNS (8.8.8.8, 8.8.4.4). 
The script creates one account. To add more, checkout `/etc/ppp/chap-secrets`.

# Installation

```
wget https://raw.githubusercontent.com/jakerullman/vpn.sh/master/vpn.sh
sudo sh vpn.sh
```
