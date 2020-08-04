
Author of dhcpdump: Edwin Groothuis http://www.mavetju.org/

This is patched version based on: https://packages.debian.org/sid/dhcpdump

dhcpdump with option to read PCAP's files created by tcpdump (or similar soft).

For my internal use :)

Added decoder for DHCP options 93,94 and 97 (https://tools.ietf.org/html/rfc4578) - PXE/net boot related.

Added arch type decoder based on https://www.ietf.org/assignments/dhcpv6-parameters/dhcpv6-parameters.xml
