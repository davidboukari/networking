# networking

## networking mask
```
## Networking
By default AWS network is class B
Mask => NB IP is some bytes which stay + 1
/32 8 8 8 8 -> 1 IPs
/31 8 8 8 7  => 2^0 + 1 => 2 IPs
/30 8 8 8 6  => 2^1 + 2^0 + 1 = 2 + 1 + 1 => 4 IPs
/29 8 8 8 5  => 2^2 + 2^1 + 2^0 + 1 = 4 + 2 + 1 + 1 => 8 IPs
/28 8 8 8 4  => 2^3 + 2^2 + 2^1 + 2^0 + 1 = 8 + 4 + 2 + 1 + 1 => 16 IPs
/27 8 8 8 3  => 2^4 + 2^3 + 2^2 + 2^1 + 2^0 + 1 = 16 + 8 + 4 + 2 + 1 + 1 => 32 IPs
...
/0 all the IPs
```
