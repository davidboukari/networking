# networking

## networking mask
```
## Networking
By default AWS network is class B
Mask => NB IP is some bytes which stay + 1
/32 8 8 8 8 -> 1 IPs
/31 8 8 8 7 => 2^0 + 1 => 2 IPs
/30 8 8 8 6 => 2^1 + 2^0 + 1 = 2 + 1 + 1 => 4 IPs
/29 8 8 8 5 => 2^2 + 2^1 + 2^0 + 1 = 4 + 2 + 1 + 1 => 8 IPs
/28 8 8 8 4 => 2^3 + 2^2 + 2^1 + 2^0 + 1 = 8 + 4 + 2 + 1 + 1 => 16 IPs
/27 8 8 8 3 => 2^4 + 2^3 + 2^2 + 2^1 + 2^0 + 1 = 16 + 8 + 4 + 2 + 1 + 1 => 32 IPs
...
/24 8 8 8 0 => 2^7 + 2^6 + 2^5 + 2^4 + 2^3 + 2^2 + 2^3 + 2^2 + 2^1 + 2^0
...
/16 8 6 0 0 => 2^15 + 2^14 + 2^13 + 2^12 + 2^11 + 2^10 + 2^9 + 2^8 + 2^7 + 2^6 + 2^5 + 2^4 + 2^3 + 2^2 + 2^3 + 2^2 + 2^1 + 2^0
...
/8 8 0 0 0  => 2^31 + 2^30 + ... + 2^15 + 2^14 + 2^13 + 2^12 + 2^11 + 2^10 + 2^9 + 2^8 + 2^7 + 2^6 + 2^5 + 2^4 + 2^3 + 2^2 + 2^3 + 2^2 + 2^1 + 2^0
...
/0 all the IPs

/32 => No IP number can change
/24 => Last IP number can change
/16 => Last IP 2 numbers can change
/8  => Last IP 3 numbers can change
/0  => All IP numbers can change
```

