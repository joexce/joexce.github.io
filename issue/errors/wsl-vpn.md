issue : no vpn connection in wsl
date : 070720

*MAIN ISSUE*
VPN windows is working, but when we try in wsl -  ubuntu 20.04 is not working

*SOLVED*
open the file /etc/resolv.conf 
add some domain name and nameserver for example:
nameserver <ip>
search <domain name>
