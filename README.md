Kernel Fork from https://github.com/aloksinha2001/picuntu-3.0.8-alok.git

tools file Fork from https://github.com/olegk0/tools.git

initramfs file Fork from https://github.com/Galland/rk30_linux_initramfs.git

How TO Use LCD?

cd marsboard-rk3066-linux-3.0.8+
make marsboard_rk3066_mtd_defconfig
make arch=ARM menuconfig

Device Drivers  --->  Graphics support  --->Display device support  --->  LCD Panel Select (RGB AT070TN93)  --->
