# Music802_ar9331_uboot
uboot for Music802 only, by modifying u-boot_mod.


## Step1
Clone this refs

## Step2
Edit your CROSS_COMPILE in rootdir's Makefile
      BUILD_PATH=/home/mrtos/work/openwrt/attitude_adjustment/staging_dir/toolchain-mips_r2_gcc-4.6-linaro_uClibc-0.9.33.2/bin
      CROSS_COMPILE=$(BUILD_PATH)/mips-openwrt-linux-
      
## Step3
make linkcard_music802
//Gen binary file: bin/uboot_for_linkcard_music802.bin
 



thanks very much [pepe2k/u-boot_mod](https://github.com/pepe2k/u-boot_mod)
