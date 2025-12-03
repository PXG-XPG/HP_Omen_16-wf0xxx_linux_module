HP Omen special feature control for Linux
-----------------------------------------

This is a version of the hp-wmi kernel module that implements some of the features of HP Omen Command Centre.

Currently working:

- Fan control(Max or Auto mode)

## Installation

1. Install dkms and kernel headers if needed (For archlinux: `sudo pacman -S dkms linux-headers`)

2. Run `sudo make install`

3. Use [omenix](https://github.com/noahpro99/omenix)

Module will be built and installed, and DKMS will manage rebuilding it on kernel updates.
