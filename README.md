# rpi gpu 
# Environment setup and testing of Raspberry Pi 3 environment,
# uses qemu to emulate a 32 bit environment for the Pi 3,
# Linux 5.1 kernel

# Using a macos (M1 Pro, 2021):
# qemu command for setting up a virtual drive in qcow2 format:

# qemu-img create -f qcow2 linux32.qcow2 10G

# Install and Start Raspian 5.1 image:

# qemu-system-x86-64 -cdrom 2022-07-01-raspios-bullseye-i386.iso -boot d -m 1024 -hda linux32.qcow2

# Ready for custom installations!

