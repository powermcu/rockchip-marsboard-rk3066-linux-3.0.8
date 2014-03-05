Kernel Fork from https://github.com/aloksinha2001/picuntu-3.0.8-alok.git

tools file Fork from https://github.com/olegk0/tools.git

initramfs file Fork from https://github.com/Galland/rk30_linux_initramfs.git

How To Build linux kernel?

./build_marsboard_rk3066_mtd
./build_marsboard_rk3066_recovery_sdcard
./build_marsboard_rk3066_sdcard

How To Use LCD?

cd marsboard-rk3066-linux-3.0.8+

make marsboard_rk3066_mtd_defconfig

make arch=ARM menuconfig

Device Drivers  --->  Graphics support  --->Display device support  --->  LCD Panel Select (RGB AT070TN93)  --->
