Kernel Fork from https://github.com/aloksinha2001/picuntu-3.0.8-alok.git

tools file Fork from https://github.com/olegk0/tools.git

initramfs file Fork from https://github.com/Galland/rk30_linux_initramfs.git

How To Build linux kernel?

get the right packages for the compiler

sudo apt-get install git-core gnupg flex bison gperf libsdl-dev libesd0-dev libwxgtk2.8-dev build-essential zip curl libncurses5-dev zlib1g-dev ia32-libs lib32z1-dev lib32ncurses5-dev gcc-multilib g++-multilib sharutils lzop

Began to compile

./build_marsboard_rk3066_mtd

./build_marsboard_rk3066_recovery_sdcard

./build_marsboard_rk3066_sdcard



How To Use LCD?

cd marsboard-rk3066-linux-3.0.8+

make marsboard_rk3066_mtd_defconfig

make arch=ARM menuconfig

use HY070CTP-A

Device Drivers  --->  Graphics support  --->Display device support  --->  LCD Panel Select (RGB AT070TN93)  --->

use HY070CTP-HD

Device Drivers  --->  Graphics support  --->Display device support  --->  LCD Panel Select (RGB AT070TNA2)  --->
