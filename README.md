# REALTEK RTL88x2B USB Linux Driver  
**Current Driver Version**: 5.6.1.6  
**Support Kernel**: 2.6.24 ~ 5.8 (with unofficial patches)  

Official release note please check ReleaseNotes.pdf  

**Note:** if you believe your device is **RTL8812BU** or **RTL8822BU** but after loaded the module no NIC shows up, the device ID maybe not in the driver whitelist. In this case please submit a new issue with `lsusb` result, and your device name, brand, website, etc.

## Supported Devices
* ASUS AC1300 USB-AC55 B1
* ASUS U2
* Dlink - DWA-181
* Dlink - DWA-182
* NetGear A6150
* Edimax EW-7822ULC
* Edimax EW-7822UTC
* TP-Link Archer T3U
* TP-Link Archer T4U V3

And more.

# How to use this kernel module
* Make sure you have installed the kernel headers
* All commands need to be run in the driver directory
* The following commands only build module for the current running kernel
* You need rebuild the kernel module everytime you update/change the kernel
## Building
```
make
```

## Installing
```
sudo make install
```

## Uninstalling
```
sudo make uninstall
```


For more details please refer to Linux Kernel Documentation.

https://www.kernel.org/doc/Documentation/kbuild/modules.txt


# Distribution
* Archlinux AUR https://aur.archlinux.org/packages/rtl88x2bu-dkms-git/
