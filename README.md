rtl8812AU_8821AU_linux
======================

rtl8812AU_8821AU linux kernel driver for AC1200 (801.11ac) Wireless Dual-Band USB Adapter

## Instructions

###Make sure you have the required build packages
sudo apt-get install linux-headers-generic build-essential git

###Download the updated source code
git clone https://github.com/scrivy/rtl8812AU_8821AU_linux.git

###Compile the kernel module
cd rtl8812AU_8821AU_linux
make

###Install it!
sudo make install
sudo modprobe 8812au

###plug in your wifi adapter and enjoy!
