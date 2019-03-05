# TP6-CCNA


# Configuration de OSPF
```
r1.tp6.b1#ping 10.6.101.2

Type escape sequence to abort.
Sending 5, 100-byte ICMP Echos to 10.6.101.2, timeout is 2 seconds:
!!!!!
Success rate is 100 percent (5/5), round-trip min/avg/max = 44/57/72 ms
```
```
r1.tp6.b1#traceroute 10.6.101.2

Type escape sequence to abort.
Tracing the route to 10.6.101.2

  1 10.6.100.6 8 msec
    10.6.100.2 20 msec
    10.6.100.6 24 msec
  2 10.6.100.10 44 msec
    10.6.100.14 24 msec
    10.6.100.10 44 msec
  3 10.6.101.2 48 msec 32 msec 44 msec
```
