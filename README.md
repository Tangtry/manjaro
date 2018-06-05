# manjaro

## Installation
choose "/boot/efi" and don't forget to check "boot" and "esp" option.
Then we can use "bootice" in windows to edit the boot menu


## Nvidia
from the official website, 
first detect the vedio card information
```
inxi -G
```
then install the drivers
```
sudo mhwd -a pci nonfree 0300
```
After installation, reboot and check if it works(always not work)
```
mhwd -li
```
And use code below to get into nvidia settings
```
optirun -b none nvidia-settings -c :8
```

## Screenfetch
To satisfy your ridiculous showing off wish
```
screenfetch -A 'Arch Linux'
```

## Themes directory
/usr/share/themes
some themes need permissions
```
sudo chmod 777 file
```
