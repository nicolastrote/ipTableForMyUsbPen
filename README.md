# ipTableForMyUsbPen
Iptables Firewall script for my debian usb pen

# How to install
$ sudo wget --no-check-certificate -O /etc/init.d/firewall.sh https://raw.githubusercontent.com/nicolastrote/ipTableForMyUsbPen
/master/firewall.sh $ sudo chmod a+x /etc/init.d/firewall.sh $ sudo update-rc.d firewall.sh defaults 20

Reboot the OS
$ sudo shutdown -r now
