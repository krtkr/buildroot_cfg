# buildroot_cfg
Some of my buildroot configurations, used in various projects.

# Build

1. clone this repo
2. get submodules
git submodule init
git submodule update
3. download recent linaro toolchain from https://www.linaro.org/latest/downloads/
4. make CROSS_ROOT={PATH_TO_LINARO}/gcc-linaro-6.4.1-2017.11-x86_64_arm-linux-gnueabihf/ O=$PWD -C ./buildroot/ -j8

