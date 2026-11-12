# ft_ping

## Overview

`ft_ping` is a simple implementation of the classic `ping` utility, which is used to test the reachability 
of a host on an Internet Protocol (IP) network. With this project I aim <b>to deepen my understanding of network communication and the underlying principles of the ICMP protocol.</b>

```python
❯ sudo ./ft_ping 8.8.8.8
[sudo] password for userr: 
PING 8.8.8.8 (8.8.8.8) 56(84) bytes of data.
64 bytes from 8.8.8.8 icmp_seq=1 ttl=116ms time=22.6 ms
64 bytes from 8.8.8.8 icmp_seq=2 ttl=116ms time=22.7 ms
64 bytes from 8.8.8.8 icmp_seq=3 ttl=116ms time=23.1 ms
64 bytes from 8.8.8.8 icmp_seq=4 ttl=116ms time=18.7 ms
64 bytes from 8.8.8.8 icmp_seq=5 ttl=116ms time=18.4 ms
^C
--- 8.8.8.8 ping statistics ---
5 packets transmitted, 5 received, 0.00% packet loss, time 4512ms
```
