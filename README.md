# gist

## Linux Stuff

```
sudo apt update && sudo apt upgrade

sudo apt-get update

sudo snap install


# snaps
slack --classic
solitaire
mc-installer
shotcut --classic
audacity
youtube-dl
gimp
sublime-text --classic

sudo apt update && sudo apt install virtualbox
https://www.teamviewer.com/en-us/


# Low
vim
synergy
atom --classic
gog-galaxy-wine
discord
htop
bobrossquotes
thunderbird --beta




[x-tile](https://www.giuspen.com/x-tile/)

# remove apt app


apt-get remove packagename

will remove the binaries, but not the configuration or data files of the package packagename. It will also leave dependencies installed with it on installation time untouched.

apt-get purge packagename or apt-get remove --purge packagename

will remove about everything regarding the package packagename, but not the dependencies installed with it on installation. Both commands are equivalent.

Particularly useful when you want to 'start all over' with an application because you messed up the configuration. However, it does not remove configuration or data files residing in users home directories, usually in hidden folders there. There is no easy way to get those removed as well.

apt-get autoremove

removes orphaned packages, i.e. installed packages that used to be installed as an dependency, but aren't any longer. Use this after removing a package which had installed dependencies you're no longer interested in.

aptitude remove packagename or aptitude purge packagename (likewise)

will also attempt to remove other packages which were required by packagename on but are not required by any remaining packages. Note that aptitude only remembers dependency information for packages that it has installed.


sudo apt-get install ubuntu-restricted-extras

# output network info
lspci | grep -i network

# commands
ps -A
ps -A | less
Pstree
Kill PID
pkill firefox
killall firefox
pgrep firefox

# What display manager?
systemctl status display-manager

# Show Hidden files
Control + H

# Open File Here
xdg-open .

# Install Deb
sudo dpkg -i /path/deb/file
sudo apt-get install -f ./

# Install Desktops - (Do at your own risk! Installs a lot of shit!) 
sudo apt-get install ubuntu-desktop
sudo apt-get install kubuntu-desktop
sudo apt-get install lubuntu-desktop
sudo apt-get install mate-desktop
sudo apt-get install ubuntu-gnome-desktop
sudo apt-get install xubuntu-desktop

# add / remove packages

sudo apt-get install <packagename>
sudo apt-get remove <packagename>
sudo apt-get purge <packagename>


```

## Links
[Example](http://google.com)

