# Radiano-Grub-Theme
elementary os inspired Grub Theme. Based on Grau theme

##Determine Supported resolution
Use this command and check the highest resolution
```sh
sudo hwinfo --framebuffer
```

or use this command in grub's console (reached by pressing c in grub)
```
videoinfo
```

##Install

Run these commands one by one
```sh
git clone https://github.com/Jguer/Radiano-Grub-Theme.git /tmp/Radiano
cd /tmp/Radiano
chmod +x install.sh
sudo ./install.sh
```
##Screenshots
Taken with camera, trying to get grub-emu to work in elementary OS and EFI.

![alt text](https://raw.githubusercontent.com/Jguer/Radiano-Grub-Theme/master/Screenshots/GRUB%201920x1080.jpg "1920x1080")

![alt text](https://raw.githubusercontent.com/Jguer/Radiano-Grub-Theme/master/Screenshots/GRUB%20640x480.jpg "640x480")

##Removing
Open up /etc/default/grub with root in your text editor of choice and find the line that says GRUB_THEME=/some/directory then comment it out (put a '#' at the beginning of the line) or erase it.

Run
```
sudo update-grub
```


Icons from Lightness for burg by SWOriginal

Respects original license of Grau http://gnome-look.org/content/show.php/Grau+GRUB+Theme?content=158610 by LegendaryBibo

Licensed under Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0)

