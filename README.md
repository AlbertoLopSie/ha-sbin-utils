# ha-sbin-utils
HomeAssitant utility scripts stored in /usr/local/sbin

It merges following repos:

# rpi-snapshot
Makes a bootable snapshot of rootfs on another partition

The idea is to be able to generate a quick snapshot of the active mounted rootfs
on another boot disk partition and optionally modify cmdline.txt on boot
partition to reboot over that image

The script modifies the fstab on cloned partition to the new partition structure

## rpi-clone

A custom versión of billw2/rpi-clone



## and another utils:

hass-backup
nxtroot
rpi-snap-log
sudoexec/sudotask
