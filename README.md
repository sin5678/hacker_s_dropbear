# hacker_s_dropbear
allow an vaild user login with empty passwd

build:
./configure --host=mipsel-buildroot-linux-uclibc   --disable-lastlog --disable-utmp --disable-utmpx --disable-wtmp --disable-wtmpx  --disable-loginfunc  --disable-pututline  --disable-pututxline --enable-static --disable-syslog --disable-zlib

make

run:
/mnt/sdcard/dropbear -p 2222 -R -B
