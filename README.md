To install on All Versions of Linux :


sudo apt-get install linux-headers-$(uname -r) build-essential git

git clone https://github.com/lukeacourt2/rtl8812AU_8...​

cd rtl8812AU_8821AU_linux

make

sudo make install

sudo modprobe rtl8812au

reboot

In future these instructions will be included in downloaded zip or when you use git function in linux
