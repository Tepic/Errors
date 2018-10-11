# Errors
UPLOADED MODPOST ERRORS

Option 1:
$ subl /etc/default/grub

Then add nomodeset to look like this:
GRUB_CMDLINE_LINUX_DEFAULT="quiet splash nomodeset

Option 2:
Trying with installing nVidia propreitary video drivers
Follow steps from here:
https://websiteforstudents.com/install-proprietary-nvidia-gpu-drivers-on-ubuntu-16-04-17-10-18-04/

Other links for this option:
1 - https://askubuntu.com/questions/851069/latest-nvidia-driver-on-ubuntu-16-04
2 - https://askubuntu.com/questions/38780/how-do-i-set-nomodeset-after-ive-already-installed-ubuntu
3 - https://www.bleepingcomputer.com/forums/t/549534/nvidia-drivers-how-to-install-it-in-ubuntu/

LINUX X64 (AMD64/EM64T) DISPLAY DRIVER
https://www.nvidia.com/Download/driverResults.aspx/136233/en-us
