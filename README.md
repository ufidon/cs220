# cs220
Online materials for CS220 - Network Fundamentals
Online materials for CS220 - Network Fundamentals

# Physical layer


# Linker layer
## Materials for Dell PowerConnect 5324
* [A usage Wiki](https://wiki.hackspherelabs.com/index.php?title=Dell_Powerconnect_5324)
* [A usage example](https://www.stevejenkins.com/blog/2011/05/dell-powerconnect-5324-setup-tasks/)
* [User manual](http://www.dell.com/support/home/us/en/04/product-support/product/powerconnect-5324/manuals)

## Open source routers
* [DD-Wrt](http://dd-wrt.com)
* [OpenWrt](https://openwrt.org)
* [VyOS](https://vyos.io/)

## Router TL-WR740Nv6
* [Reset password](http://www.tp-link.com/us/faq-426.html)
* [Tftp secret of TL-WR740N](http://bkil.blogspot.hu/2014/12/tftp-secret-of-tl-wr740n-uncovered.html)
* [Hidden TFTP of TP-Link routers](http://bkil.blogspot.com/2014/12/hidden-tftp-of-tp-link-routers.html)
* [Installing OpenWrt via TFTP](https://wiki.openwrt.org/doc/howto/generic.flashing.tftp)

## Router NETGEAR R6300v2
* [R6300v2 – Smart WiFi Router AC1750 Dual Band Gigabit](https://www.netgear.com/support/product/r6300v2)
* [DD-Wrt for Netgear R6300 v2](http://www.dd-wrt.com/wiki/index.php/Netgear_R6300v2)
* [OpenWrt for Netgear R6300 v2](https://wiki.openwrt.org/toh/netgear/netgear_r6300_v2)

## ARP softwares
* [ARP Scannet](https://sourceforge.net/projects/arpscannet/)
* [ARP AntiSpoofer](https://sourceforge.net/projects/arpantispoofer/)
* [A list of ARP softwares](http://www.findbestopensource.com/tagged/arp?start=10)


# Wireless Network
* [Virtual Router - Wifi Hot Spot for Windows 8, Windows 7 and 2008 R2](https://virtualrouter.codeplex.com/)
* [Virtual Router Plus](http://virtualrouterplus.com/)
* [How to Turn Your Windows PC Into a Wi-Fi Hotspot](http://www.howtogeek.com/214080/how-to-turn-your-windows-pc-into-a-wi-fi-hotspot/)
* [How to Turn Your Ubuntu Laptop into a Wireless Access Point](http://www.howtogeek.com/116409/how-to-turn-your-ubuntu-laptop-into-a-wireless-access-point/)
* [Share an Internet Connection Between Wireless Machines with an Ad Hoc Network in Windows 7](http://www.howtogeek.com/howto/21943/share-an-internet-connection-between-wireless-machines-with-an-ad-hoc-network-in-windows-7/)
* [What’s the Difference Between Ad-Hoc and Infrastructure Mode Wi-Fi?](http://www.howtogeek.com/180649/htg-explains-whats-the-difference-between-ad-hoc-and-infrastructure-mode/)

# Application layer
## BOOTP server
* [BOOTPd server](http://bootpdnis.sourceforge.net/)

## DHCP
* [Open DHCP Server](http://dhcpserver.sourceforge.net/)
* [Dual DHCP DNS Server](http://dhcp-dns-server.sourceforge.net/)
* [A DHCP server for Windows](http://www.dhcpserver.de/cms/)
* [A list of DHCP server softwares from wikipedia](https://en.wikipedia.org/wiki/Comparison_of_DHCP_server_software)

## DNS
* [DNS over LAN](http://unix.stackexchange.com/questions/16890/how-to-make-a-machine-accessible-from-the-lan-using-its-hostname)
* [How To Access Your Machines Using DNS Names with DD-WRT](http://www.howtogeek.com/69696/how-to-access-your-machines-using-dns-names-with-dd-wrt/)
* [A list of DNS server softwares from wikipedia](https://en.wikipedia.org/wiki/Comparison_of_DNS_server_software)


## TFTP servers for Windows
* [Open TFTP Server](https://sourceforge.net/p/tftp-server/wiki/Home/)
* [Tftpd32](http://tftpd32.jounin.net/)


## HTTP servers
* [Apache](https://httpd.apache.org/)
* [nginx](https://www.nginx.com/)

## FTP servers
* [FileZilla](https://filezilla-project.org/)
* [acftp](https://sourceforge.net/projects/acftp/)
* [SFTP servers](http://www.sftp.net/servers)

## email
* email server: 
  * [hMailServer](https://www.hmailserver.com)
  * [iRedMail](http://www.iredmail.org/)
  
* web mail:
  * [SquirrelMail](http://squirrelmail.org)
  * [roundcube](https://roundcube.net/)

# Network analyzing tools
* package capture:
  * [Win10pcap](http://www.win10pcap.org)
  * [Wireshark](https://www.wireshark.org/)
  
## WireShark
Install wireshark on Ubuntu
```bash
$ sudo apt-get install wireshark
$ sudo dpkg-reconfigure wireshark-common 
$ sudo usermod -a -G wireshark $USER
$ gnome-session-quit --logout --no-prompt
```

* wireless network detection
  * [NetStumbler](http://www.stumbler.net/)
  * [Vistumbler](https://www.vistumbler.net/)
  * [Kismet Wireless](http://www.kismetwireless.net/)
  
# Network monitoring and management tools
* [Cacti](http://www.cacti.net)  
* [Nagios](https://www.nagios.org/)
* [Icinga](https://www.icinga.com/)
* [Nedi](http://www.nedi.ch/)
* [A list from wikipedia](https://en.wikipedia.org/wiki/Comparison_of_network_monitoring_systems)

# Authentication
* [FreeRADIUS](http://freeradius.org/)
* [Freeradius](http://www.freeradius.net)
* [WinRADIUS](http://winradius.eu)
* [OpenAAA](http://openaaa.sourceforge.net/)

# Network raw programming
* [PACKETH](http://packeth.sourceforge.net/packeth/Home.html)
* [Raw Ethernet Packet Sending](https://www.codeproject.com/articles/5292/raw-ethernet-packet-sending)
* [System.Net.NetworkInformation Namespace](https://msdn.microsoft.com/en-us/library/system.net.networkinformation.aspx)
* [WinPCAP](http://www.winpcap.org/)
* [OpenFlow](http://archive.openflow.org/)
* [Mininet](http://mininet.org/)
