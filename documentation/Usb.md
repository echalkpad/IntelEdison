USB
==

## Userspace Applications

    root@edison:~# dmesg
    root@edison:~# lsusb
    unable to initialize libusb: -99

## Setup
### Opkg

    root@Edison:~# opkg install libusb-1.0-dev libudev1-dev

### Apt-Get

    root@Edison:~# apt-get install libusb-1.0-dev libudev-dev
    root@Edison:~# libtool
    
    root@Edison:~# git clone https://github.com/libusb/libusb.git
    root@Edison:~# cd libusb
    root@Edison:~# ./autogen.sh -disable-udev
    root@Edison:~# make
    root@Edison:~# cd examples

## Links

- http://www.yoctopuce.com/