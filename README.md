# Uboot Flashforge
#### Uboot for Flashforge Adventurer 3 / Monoprice Voxel / others (with Widora web recovery)
***
# How to build
* 1. make menuconfig
* 2. select MT7628 board
* 3. make clean;make

# Recover dead printer
* 1. download the release package or build from source (you'll need to pad `uboot.bin` to the size of your flash if you build it)
* 2. use a soic clip to flash `uboot.rom` to the flash chip near the Mediatek SOC
* 3. download stock firmware for your printer
* 4. extract your kernel e.g. `Adventurer3-1.2.5-1.6-20210329.tgz > . > kernel-1.0.0.tar.xz > . > uImage-adventurer3-20180831`
* 5. todo

### Note
* compilation requires java such as 1.7.0_79

* based on https://github.com/widora/u-boot-mt7688
## Thanks to Manfeel, cleanwrt, Piotr Dymac, Adam Dunkels.
