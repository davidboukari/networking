# networking

## networking mask
```
By default AWS network is class B
Mask => NB IP is some bytes which stay + 1
32 8 8 8 8 -> 1 IP
31 8 8 8 7  => 2^0 + 1 => 2 IP
30 8 8 8 6  => 2^1 + 2^0 + 1 = 2 + 1 + 1 => 4 IP
29 8 8 8 5  => 2^2 + 2^1 + 2^0 + 1 = 4 + 2 + 1 + 1 => 8 IP
28 8 8 8 4  => 2^3 + 2^2 + 2^1 + 2^0 + 1 = 8 + 4 + 2 + 1 + 1 => 16 IP
27 8 8 8 3  => 2^4 + 2^3 + 2^2 + 2^1 + 2^0 + 1 = 16 + 8 + 4 + 2 + 1 + 1 => 32 IP
```
