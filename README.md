## What's this
Tiny tool for writing a kernel module

## Usage
```
$ kmodinit hello
$ ls ./
Makefile  hello.c
$ make
$ make insmod
$ lsmod | grep hello
hello                    857  0
$ make rmmod
$ lsmod | grep hello
```
