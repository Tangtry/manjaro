# manjaro

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
