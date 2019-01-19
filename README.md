# pi-helpers
small helper scripts to configure pi's

## Commands

`accesspoint` opens a public access point, free for all, deactivates dhcpcd, serves own ip addresses and dns, NAT traffic via eth0. Currently hardcoded to channel 8, fixed essid and wlan0 interface. *Will be more flexible in the future*

`adhocwifi <wlan_interface>` Puts interface into ad-hoc mode and sets an IP address in the 10.0.0.0/8 range, hopefully unique since derived from the interface mac address.

`installdocker` Downloads and installs the latest version of docker.

`installnodejs <version>` Downloads and installs the specified version (eg. 10, 9, 8,) of nodejs.

`sethostname <hostname>` Sets the hostname on the system.

`setuniquehostname <hostnameprefix>` Sets the hostname to the specified prefix plus the hex representation of the CPU hardware serial number of the raspberry pi.

