# manjaroInstalling
### For Manjaro linux installing on Vm ware 
Its important to set on the 'grub' file at /etc/default/grub 

Edit the grub file with super user authenticated
### sudo vi /etc/default/grub 

search for GRUB_GFXMODE = auto 
and change to:
### GRUB_GFXMODE = 1920X1080X32 

Save the file.

Then 
In the terminal type: 
### sudo update-grub 

Done. 
Reboot your system and its going to change automatically to right resolution

