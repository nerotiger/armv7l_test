# armv7l_test
hello world under RPI3B+

```
-rwxr-xr-x 1 pi pi    8144 Jun 23 19:54 c_a
-rwxr-xr-x 1 pi pi 1900185 Jun 23 19:51 go_a
```
```
pi@raspberrypi:/tmp $ time ./c_a
hello world

real	0m0.006s
user	0m0.001s
sys	0m0.005s
```
```
pi@raspberrypi:/tmp $ time ./go_a 
hello world

real	0m0.008s
user	0m0.000s
sys	0m0.009s
```

```
c_a:  ELF 32-bit LSB executable, ARM, EABI5 version 1 (SYSV), dynamically linked, interpreter /lib/ld-linux-armhf.so.3, for GNU/Linux 3.2.0, BuildID[sha1]=ba3f77c784053e438376f0ff495fb8bc5c9c6cff, not stripped
```
```
go_a: ELF 32-bit LSB executable, ARM, EABI5 version 1 (SYSV), statically linked, not stripped
```
