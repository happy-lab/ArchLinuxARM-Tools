#Arch Linux ARM Installation Notes

Notes on a method to install Arch Linux on popular ARM boards.  Probably only of personal interest, ...

## License
Internet Monitor is released under a liberal BSD-style [license](./License.txt).

## Installation
Follow the installation for the board on the [Arch Linux ARM site](https://archlinuxarm.org) site.

### Creating The Memory Device
The *arm-install* script in this repository provides a basis for RaspBerry Pi boards.  The above script is run on a Linux system running Fedora.

### Configuration
Before the memory device and the board is powered on, the board's serial port is attached to terminal emulator.  After the board is powered on, log into the system as root.  Cut-and-paste the commands from the appropriate text files as needed, starting with *archlinux-arm-install.txt*.
