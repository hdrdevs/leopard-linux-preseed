LISTADO DE COMANDOS UTILIZADOS
==============================

sudo apt update
sudo su
nano /etc/sudoers
sudo su
su
clear
sudo apt update
clear
sudo apt install gigolo
sudo apt search appmenu
clear
sudo apt search chromium
sudo apt install compiz compiz-plugins compizconfig-settings-manager dconf-editor plank appmenu appmenu-gtk-module-common appmenu-gtk2-module appmenu-gtk3-module appmenu-registrar libappmenu-gtk-parser-dev-common libappmenu-gtk2-parser0 libappmenu-gtk3-parser0 vala-panel-appmenu vala-panel-appmenu-common xfce4-appmenu-plugin chromium mesa-utils synapse neofetch htop lightdm-gtk-greeter-settings audacious fonts-crosextra-carlito gnome-font-viewer git
sudo apt install compiz compiz-plugins compizconfig-settings-manager dconf-editor plank appmenu-gtk-module-common appmenu-gtk2-module appmenu-gtk3-module appmenu-registrar libappmenu-gtk-parser-dev-common libappmenu-gtk2-parser0 libappmenu-gtk3-parser0 vala-panel-appmenu vala-panel-appmenu-common xfce4-appmenu-plugin chromium mesa-utils synapse neofetch htop lightdm-gtk-greeter-settings audacious fonts-crosextra-carlito gnome-font-viewer git
sudo dpkg -i plank-cratos-lion-3.1\ \(1\).deb 
xfconf-query -c xsettings -p /Gtk/ShellShowsMenubar -n -t bool -s true
xfconf-query -c xsettings -p /Gtk/ShellShowsAppmenu -n -t bool -s true
xfconf-query -c xsettings -p /Gtk/Modules -n -t string -s "appmenu-gtk-module"
sudo chown -R horacio:horacio /usr/share/icons/
sudo chown -R horacio:horacio /usr/share/themes/
ls -la fonts.svg 
ls -la gnome-power
ls -la gnome-power-manager.svg 
ls -la gthumb.svg 
ls -la session-properties.svg 
ls -la gnome-settings-accessibility-technologies.svg 
ls -la gnome-desktop-config.svg 
ls -la gnome-panel-workspace-switcher.svg 
ls -la xfwm4.svg 
ls -la wmtweaks.svg 
sudo apt install gimp inkscape
sudo dpkg -i Downloads/code_1.82.2-1694671812_amd64.deb 
sudo chown -R horacio:horacio /usr/share/applications
sudo apt autoremove firefox-esr 
sudo apt install rofi
cd Downloads/
git clone https://github.com/lr-tech/rofi-themes-collection.git
mkdir -p ~/.local/share/rofi/themes/
rofi-theme-selector 
rofi
touch ~/.config/rofi/config.rasi
mkdir Desarrollo
cd Desarrollo/
git clone http://192.168.1.70:8020/horacio/turnosreact.git
git config --global user.name "Horacio Daniel Ros"
git config --global user.email "horaciodrs@gmail.com"
cd Desarrollo/turnosreact/
ls
sudo apt install nodejs npm
sudo apt search tlp
sudo apt install tlp
sudo systemctl enable tlp
sudo systemctl status tlp
sudo powertop 
powertop --calibrate
sudo powertop --calibrate 
cd ~/.local/share/rofi/
ls
cd themes/
ls
sudo apt install vim
clear
vim launchpad.rasi 
exit
sudo apt install redshift
redshift 
sudo apt search geoclue
clear
sudo vim /etc/geoclue/geoclue.conf 
redshift -gtk
redshift
sudo redshift 
glxgears
redshift-gtk
redshift -gtk
sudo apt search gamma
sudo redshift -gtk
sudo apt search nightli
sudo apt search nigthli
neofetch 
sudo apt autoremove redshift 
clear
sudo apt autoclean 
exit
sudo apt search bluetooth
sudo apt install blueman 
cd Downloads/
sudo mount -o loop, rw debian-12.1.0-amd64-netinst.iso cdrom
sudo mount -o loop, rw debian-12.1.0-amd64-netinst.iso /home/horacio/Downloads/cdrom
sudo mount -o loop, rw debian-12.1.0-amd64-netinst.iso cdrom/
sudo mount -o loop, rw debian-12.1.0-amd64-netinst.iso cdrom/ -v
sudo mount -v -o loop, rw debian-12.1.0-amd64-netinst.iso cdrom/
sudo mount -o loop,rw -v debian-12.1.0-amd64-netinst.iso ~/Downloads/cdrom/
sudo chown -R horacio:horacio cdrom/
sudo apt-get install libarchive-tools
ls
cd cdrom/
ls
cd ..
bsdtar -C cdrom -xf debian-12.1.0-amd64-netinst.iso
cd cdrom/
ls
cd ..
sudo chown -R horacio:horacio cdrom/
sudo chmod -R 777 cdrom/
mkisofs -o /home/horacio/leopard.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 -quiet -preseed /home/horacio/Downloads/cdrom/install/preseed.cfg -graft-points /home/horacio/Downloads/cdrom=/mnt/debian /home/horacio/Downloads/cdrom/pool/post-install.sh=/root/post-install.sh
sudo apt-get install genisoimage
mkisofs -o /home/horacio/leopard.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 -quiet -preseed /home/horacio/Downloads/cdrom/install/preseed.cfg -graft-points /home/horacio/Downloads/cdrom=/mnt/debian /home/horacio/Downloads/cdrom/pool/post-install.sh=/root/post-install.sh
mkisofs -o /home/horacio/leopard.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 -quiet -preseed /home/horacio/Downloads/cdrom/install/preseed.cfg -R /home/horacio/Downloads/cdrom /home/horacio/Downloads/cdrom/pool/post-install.sh=/root/post-install.sh
mkisofs -o /home/horacio/debian.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 -quiet -preseed /home/horacio/preseed.cfg -R /home/horacio/Downloads/cdrom /home/horacio/post-install.sh=/root/post-install.sh
mkisofs -o /home/horacio/debian.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 -quiet -preseed /home/horacio/preseed.cfg -graft-points /home/horacio/Downloads/cdrom /home/horacio/post-install.sh=/root/post-install.sh
mkisofs -o /home/horacio/debian.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 -quiet -graft-points /home/horacio/Downloads/cdrom
sudo apt install qemu-kvm libvirt-clients libvirt-daemon-system bridge-utils virtinst libvirt-daemon
sudo apt install virt-manager -y
mkisofs -o /home/horacio/debian2.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 -quiet -graft-points /home/horacio/Downloads/cdrom
mkisofs -o /home/horacio/debian2.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat iso-preseed
cd Downloads/cdrom/
mkisofs -o /home/horacio/debian2.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 -isopreseed
mkisofs -o /home/horacio/debian2.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 -iso-preseed
mkisofs -o /home/horacio/debian2.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 iso-preseed
genisoimage -o /home/horacio/debian2.iso -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat -input-charset utf-8 iso-preseed
genisoimage -o /home/horacio/debian2.iso -l -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat  iso-preseed
genisoimage -o /home/horacio/debian2.iso -l -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat  -iso-preseed
genisoimage -o /home/horacio/debian2.iso -l -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat iso-preseed
cd
genisoimage -o /home/horacio/debian2.iso -l -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat /home/horacio/Downloads/cdrom/
cd Desarrollo/
git clone https://github.com/hdrdevs/leopart-post-install.git
ls
sudo rm -r leopart-post-install/
genisoimage -o /home/horacio/debian2.iso -l -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat /home/horacio/Downloads/cdrom/
ssh-keygen -t ed25519 -C "horaciodrs@gmail.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
cat ~/.ssh/id_ed25519.pub
cd Desarrollo/
ls
git clone git@github.com:hdrdevs/leopard-post-install.git
git clone git@github.com:hdrdevs/leopard-linux-preseed.git
cp /etc/os-release os-release
genisoimage -o /home/horacio/leopard-linux1-amd64.iso -l -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat /home/horacio/Downloads/cdrom/
sudo apt search lightdm
sudo apt search lightdm-webkit
sudo apt-get install lightdm-webkit2-greeter
sudo apt get update
sudo apt update
sudo apt search lightdm-webkit
sudo nano /etc/apt/sources.list
sudo apt update
sudo apt search lightdm-webkit
sudo apt search lightdm
sudo thunar
genisoimage -o /home/horacio/leopard-linux1-amd64.iso -l -r -J -no-emul-boot -boot-load-size 4 -boot-info-table -b isolinux/isolinux.bin -c isolinux/boot.cat /home/horacio/Downloads/cdrom/
ls -la desktop-grub
ls -la
cd Desarrollo/
git clone git://anonscm.debian.org/d-i/debian-installer.git
git clone git://194.177.211.202/d-i/debian-installer.git
git clone git://mirror.us-midwest-1.nexcess.net/debian-installer.git
ls
exit
ls -la os-release 
cd /usr/share/images/desktop-base/
ls -la
ln -s /etc/alternatives/desktop-login-background
ls -a /etc/alternatives/desktop-login-background
ls -la /etc/alternatives/desktop-login-background
sudo apt search menu-editor
sudo apt search menu editor
sudo apt install alacarte 
neofetch 
gzip -d < initrd.gz | cpio -id
ccsm
ls -la
sudo apt install transmission
