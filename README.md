# ext2tools



export PATH=/busybox-virtual:/data/data/com.n0n3m4.droidc/files/:/data/data/com.n0n3m4.droidc/files/gcc/bin:/data/data/com.n0n3m4.droidc/files/gcc/arm-linux-androideabi/bin/:$PATH
export CC="arm-linux-androideabi-gcc -pie -I/data/data/com.n0n3m4.droidc/files/gcc/arm-linux-androideabi/include/ncurses"
export CXX="arm-linux-androideabi-g++ -pie -I/data/data/com.n0n3m4.droidc/files/gcc/arm-linux-androideabi/include/ncurses"
export SHELL="/data/data/com.n0n3m4.droidc/files/busybox sh"
cd "/storage/emulated/0/Github/ext2tools/"
make CC="$CC" CXX="$CXX" SHELL="$SHELL"
echo "errorcode:$?"
echo "exit""term"
exit
/ $ export PATH=/busybox-virtual:/data/data/com.n0n3m4.droidc/files/:/data/data/com.n0n3m4.droidc/files/gcc/bin:/data/data/com.n0n3m4.droidc/files/gcc/arm-linux-androideabi/bin/:$PATH
/ $ export CC="arm-linux-androideabi-gcc -pie -I/data/data/com.n0n3m4.droidc/files/gcc/arm-linux-androideabi/include/ncurses"
/ $ export CXX="arm-linux-androideabi-g++ -pie -I/data/data/com.n0n3m4.droidc/files/gcc/arm-linux-androideabi/include/ncurses"
/ $ export SHELL="/data/data/com.n0n3m4.droidc/files/busybox sh"
/ $ cd "/storage/emulated/0/Github/ext2tools/"
/storage/emulated/0/Github/ext2tools $ make CC="$CC" CXX="$CXX" SHELL="$SHELL"
make -C e2p
make[1]: Entering directory '/storage/emulated/0/Github/ext2tools/e2p'
arm-linux-androideabi-gcc -pie -I/data/data/com.n0n3m4.droidc/files/gcc/arm-linux-androideabi/include/ncurses -O0 -g -I -DHAVE_ERRNO_H -DHAVE_SYS_STAT_H -DHAVE_UNISTD_H -I. -I.. -c fgetflags.c
fgetflags.c: In function 'fgetflags':
fgetflags.c:93:2: error: 'errno' undeclared (first use in this function)
  errno = EOPNOTSUPP;
  ^
fgetflags.c:93:2: note: each undeclared identifier is reported only once for each function it appears in
Makefile:6: recipe for target 'fgetflags.o' failed
make[1]: *** [fgetflags.o] Error 1
make[1]: Leaving directory '/storage/emulated/0/Github/ext2tools/e2p'
Makefile:5: recipe for target 'all' failed
make: *** [all] Error 2
/storage/emulated/0/Github/ext2tools $ echo "errorcode:$?"
errorcode:2
/storage/emulated/0/Github/ext2tools $ echo "exit""term"
exitterm
