before building 3rd directory, you may need to run this:


for debian users:

open sources.list file

vi /etc/apt/sources.list

append ‘contrib’ and ‘non-free’ to repo URL like this

deb  http://deb.debian.org/debian stretch main contrib non-free
deb-src  http://deb.debian.org/debian stretch main

deb  http://deb.debian.org/debian stretch-updates main contrib non-free
deb-src  http://deb.debian.org/debian stretch-updates main

deb http://security.debian.org/ stretch/updates main contrib non-free
deb-src http://security.debian.org/ stretch/updates main

then run install

$>sudo apt install git linux-headers-$(uname -r) nvidia-driver nvidia-settings nvidia-xconfig cmake g++ xorg-dev libx11-dev automake autoconf autotools-dev libtool nasm tcl-dev g++-arm-linux-gnueabihf

if it's the first time installing nvidia driver, please reboot before build this library.
