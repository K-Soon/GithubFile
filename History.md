History Of Kanoe
--- google-chrome-stable 6.1.21.49
--- netease-cloud-music 6.1.21.54
--- code 6.1.21.56
//--- steam-installer 6.1.22.03
//--- VMware-Workstation 6.1.23.02
//--- gcc 6.1.23.04
//--- libcanberra* 6.1.23.14
--- wps-office 6.2.07.56
--- pada5.1.0-x86_64.appimage 6.2.08.21
--- vim 6.2.13.30
//--- net-tools 6.2.16.18
--- wget -O- https://deepin-wine.i-m.dev/setup.sh | sh
--- sudo apt install deepin.com.qq.im 6.2.17.31
--- gnome-tweaks 6.2.17.59
--- gnome-shell-extensions 6.2.19.13
//--- htop 6.2.20.58
//--- chrome-gnome-shell
//--- gnome-shell-extension-autohidetopbar 6.2.21.05//remove
//--- git 6.2.21.46
//--- gnome-tweak-tool 6.2.21.49
//--- ubuntu-desktop 6.2.22.37//remove
//--- dash to dock 6.2.22.38
//--- sudo apt install gir1.2-gtop-2.0 6.2.23.34//remove
//--- sudo apt install winetricks 6.3.10.14//remove
//--- fcitx 6.3.19.26	//app shop
--- rdfind 6.4.10.52
//--- fdupes 6.13.19.30
--- fonts-wqy-microhei	/*
--- fonts-wqy-zenhei	*correct the font of QQ 6.10.21.43
--- xfonts-wqy		*/
--- sudo apt install fcitx5* kde-config-fcitx5// ~/.pam_environment:add  GTK_IM_MODULE DEFAULT=fcitx5 \n QT_IM_MODULE  DEFAULT=fcitx5 \n XMODIFIERS    DEFAULT=@im=fcitx5
//--- aptitude
//--- ubuntu-20.04-change-gdm-background //to change background
--- imagemagick //image convert
--- systemback//sudo add-apt-repository "deb http://ppa.launchpad.net/nemh/systemback/ubuntu xenial main" /****/sudo apt update 
--- sudo apt install ntpdate  /sudo ntpdate time.windows.com  /sudo hwclock --localtime --systohc //double system correct date
//--- sudo add-apt-reposutory ppa:shemgp/gnome-40	  /sudo apt install gnome-tweaks chrome-gnome-shell sassc optipng inkscape libcanberra-gtk-module libglib2.0-dev libxml2-utils //gnome 40
---wget -qO - https://typora.io/linux/public-key.asc | sudo apt-key add -
---sudo add-apt-repository 'deb https://typora.io/linux ./'
---sudo apt-get install typora
--- sudo apt-get install cmake xz-utils build-essential wget -y
--- sudo apt-get install llvm clang flex bison -y
