```
git clone -b 2021.02.x https://github.com/buildroot/buildroot
cd ./buildroot/
make distclean
make freescale_imx8mqevk_defconfig
make -j12
```
