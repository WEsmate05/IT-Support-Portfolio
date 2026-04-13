Case 1 – Summary

Case 1 analyses an IPv6 packet capture containing ICMPv6 traffic between two local hosts (fe80::2 and fe80::1). The capture consists mainly of Neighbor Discovery Protocol messages and ICMPv6 Echo Request/Reply traffic used for connectivity testing and address resolution.

The communication begins with standard neighbor solicitation and advertisement exchanges, followed by repeated echo requests and replies confirming successful connectivity between both hosts. After packet 32, ICMPv6 echo replies from fe80::1 stop, although occasional Neighbor Advertisements continue, indicating the host remains active but is no longer responding to ICMP echo requests. This behaviour is most likely due to ICMP filtering or configuration changes. No malicious activity is observed.
