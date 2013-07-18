strace sources
--------------

Can be accessed through:
git clone git://git.code.sf.net/p/strace/code strace-code

How to build a static binary:
> ./configure

Add " -static" to the definition of CFLAGS in Makefile

> make
> strip strace
