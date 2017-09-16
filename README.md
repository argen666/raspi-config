# raspi-config.github.io

cmdline.txt

dwc_otg.lpm_enable=0 console=serial0,115200 console=tty1 root=/dev/mmcblk0p2 rootfstype=ext4 elevator=deadline fsck.repair=yes logo.nologo vt.global_cursor_default=0 rootwait quiet init=/usr/lib/raspi-config/init_resize.sh
