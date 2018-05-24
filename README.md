# gnu-arm-toolchain-installer
Script will install gnu-arm-toolchain for osmocombb
This toolchain in contrast to the [original]: https://osmocom.org/attachments/download/2052/gnu-arm-build.3.sh uses gcc 4.9.4
Newlib will compiled with the parameter __--disable-newlib-supplied-syscalls__ because without it, it is not compile.
