# Software setup for BB-CH340T

Old Linux driver has bug with PLL settings not allowing CH340T to work over 115200 bps.

This is fixed in Linux Kernel 5.5 and up, but if you have Linux with old kernels you can fix this by following: 

https://github.com/OLIMEX/ch340-dkms
