# Griggorii@gmail.com

Danger ! Experimental programming my idea FRAMEBUFFER=Y backup original initramfs.conf

1) variant sudo gedit /etc/initramfs-tools/initramfs.conf copy text paste https://github.com/Griggorii/-etc-initramfs-tools-initramfs.conf/blob/master/initramfs.conf save

2) variant download https://github.com/Griggorii/-etc-initramfs-tools-initramfs.conf/blob/master/initramfs.conf run admin as explorer (nemo | thunar | nautilus all ) /etc/initramfs-tools  replace initramfs.conf


SU  && update-initramfs -u -v && update-initramfs -u && update-grub
