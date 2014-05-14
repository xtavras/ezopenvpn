##ezopenvpn
=========

OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian-based distros, based on Nyr's [openvpn-install](https://github.com/Nyr/openvpn-install) script

This script will let you setup your own VPN server in no more than one minute, even if you haven't used OpenVPN before. It isn't bulletproof but it has been designed to be as unobtrusive and universal as possible.

###Installation
Run the script and follow the assistant:

`wget https://raw.github.com/cwaffles/ezopenvpn/master/ezopenvpn.sh --no-check-certificate -O ezopenvpn.sh; chmod +x ezopenvpn.sh; ./ezopenvpn.sh`

Once it ends, you can run it again to add more users.

###New features
- Automatic inline .ovpn file generation for Android devices
- Google DNS servers
- Port 53 enabled by default for captive portal bypass

###I want to run my own VPN but don't have a server for that
There are reliable providers where you can get a little VPS for even less than one buck a month.

- [Secure Dragon (Tampa, FL - Denver, CO - Los Angeles, CA - Chicago, IL)](https://securedragon.net/openvz.php)
- [High Speed Web (Los Angeles, CA)](http://www.highspeedweb.net/)
- [IperWeb (Dallas, TX)](http://my.iperweb.com/cart/)
- [HTTP Zoom (Berkshire, UK)](http://httpzoom.com/)

If you don't care about sharing an IP address with more people, you should check out the awesome [LowEndSpirit](http://lowendspirit.com/) project. They are providing IPv6-only VPS with NATed IPv4 for only 3€/year.
