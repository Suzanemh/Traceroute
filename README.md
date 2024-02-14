# Traceroute
Internet Routes with traceroute / tracert

# tracerout..
enables you to trace the complete route from your computer to a remote system. You can specify
the destination node using either a domain name (e.g., www.google.com) or an IP address (e.g., 113.2.44.1).

# Task
Perform a traceroute to www.google.com. Explain how traceroute discovers a path to a remote host in traceroute-yourid.txt.

# Input
Traceroute % traceroute google.com

# Output
traceroute to google.com (216.58.207.238), 64 hops max, 52 byte packets
 1  devicesetup.net (192.168.0.1)  5.552 ms  3.560 ms  3.500 ms
 2  * * *
 3  cm-84.208.24.252.get.no (84.208.24.252)  4.846 ms  39.070 ms  6.198 ms
 4  109-163-76-160.telia-isp.no (109.163.76.160)  4.192 ms  4.129 ms  4.443 ms
 5  oso-b1-link.ip.twelve99.net (62.115.175.156)  9.069 ms  11.086 ms  6.441 ms
 6  s-bb1-link.ip.twelve99.net (62.115.116.101)  11.034 ms  11.619 ms  11.304 ms
 7  s-b2-link.ip.twelve99.net (62.115.140.215)  12.641 ms  12.649 ms  10.764 ms
 8  72.14.196.176 (72.14.196.176)  11.587 ms
    72.14.205.198 (72.14.205.198)  13.328 ms
    72.14.219.132 (72.14.219.132)  16.632 ms
 9  * * *
10  108.170.254.33 (108.170.254.33)  19.414 ms  14.846 ms  13.753 ms
11  209.85.242.83 (209.85.242.83)  14.932 ms
    108.170.254.50 (108.170.254.50)  13.366 ms
    108.170.254.38 (108.170.254.38)  14.448 ms
12  arn09s19-in-f14.1e100.net (216.58.207.238)  13.808 ms
    108.170.253.177 (108.170.253.177)  11.298 ms  11.253 ms