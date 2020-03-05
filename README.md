# mac-os-theme  
resources can be downloaded from [here](https://drive.google.com/open?id=1DmAJkjtWmhmQOrvM5MlZv9lCBF6EnSg4)


*mac-plymouth* is also included!

# Instructions:
1)Create *.themes* and *.icons* folder in your *home* directory  

2)From the downloaded resources copy paste the *Mc-OS-Transparent-1.1*  folder into *.themes* folder  

3)The *Os-Catalina-icons* folder should be placed in your *.icons* folder 

4)Use *gnome-tweaks* to change your *theme* and *icons*

5)*gnome-tweaks* can be installed using this command  
`sudo apt-get install gnome-tweaks`  
# changing your plymouth (a.k.a splash screen):  
1. copy file to *usr/share/plymouth/themes*  
2. run in terminal:  
`sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/apple-mac-plymouth/apple-mac-plymouth.plymouth 100`  
`sudo update-alternatives --config default.plymouth`  
`sudo update-initramfs -u`
## that's it you have your mac os look alike desktop
