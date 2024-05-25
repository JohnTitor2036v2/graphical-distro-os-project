# graphical-distro-os-project
A minimal graphical distribution based on nanox/microwindows with capabilities to display X11 applications. Made for university OS course as final project.

## Requirements
  • qemu-system-x86_64
  • Minimum of 200 MB of storage on hard drive 

## How to use
  • Starting qemu virtualization with "qemu-system-x86_64 boot.img -vga cirrus"
  • The distribution cannot boot automatically, thus it has to be done manually "/bzImage rw root=/dev/sda
  • To start the graphical environment, /nanox/nano-X should be run.
  • All applications are stored in /nanox/, where they can be started with “./ application_name”
