# Supremo-installer
A simple helper script to install SupRemo remote control in GNU/Linux based in [mriza/winbox-installer](https://github.com/mriza/winbox-installer) repository.

## Features:
1. Supported GNU/Linux distributtions: Debian, Ubuntu, Elementary OS, Zorin OS, Linux Mint, Kali Linux, Fedora, RHEL, CentOS, IGOS Nusantara, Archlinux
2. Installs wine
3. Upgrades wine (from the distribution's repo) to a newer version (only for Fedora, RHEL, CentOS, IGN)
4. Menu entry in the application launcher
5. Startup Supremo on login
6. Latest Supremo from https://www.supremocontrol.com/download.aspx?file=Supremo.exe&id_sw=7&ws=supremocontrol.com

## How to install:
Copy and paste this commands to your terminal:

1. `cd /tmp`
2. `git clone https://github.com/NauelG/supremo-installer.git`
3. `cd supremo-installer`
4. `sudo ./supremo-setup install` **OR** `sudo sh supremo-setup install`


## Icon cache in GTK based desktop:
Optional step for GTK based desktop, if the icon is not loaded or loaded with wrong size. Update icon cache with this command:

`gtk-update-icon-cache -f -t /usr/share/icons/hicolor`

## How to remove:
If you want to remove winbox, just run this command:

`sudo ./supremo-setup remove` **OR** `sudo ./supremo-setup remove`
