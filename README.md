My-arch-packages
================

## About this
This is the list of packages that I use on my Manjaro KDE laptop at work

List of installed stuff:

- Firefox
- Chromium
- Sonos
- Telegram / Whatsapp
- Teamviewer 12
- Vmware Workstation
- Shrew SoftVPN Client for older vpn systems
- Veeam Agent for linux
- Etc ...

## Dependencies
Manjaro KDE 18.04 fully up to date with kernel 5.0

## Tested on
- Dell XPS 9350
- Hp EliteBook 1040 g3

## Installation

Installing base packages:

```bash
cd /tmp
wget https://raw.githubusercontent.com/stylersnico/My-arch-packages/master/pkglist.txt
sudo pacman -S --needed --noconfirm < pkglist.txt
```

Installing yaourt (I prefer this one):

```bash
sudo pacaur -S yaourt
```

Installing AUR packages (this will take a loonnnngggg time):

```bash
cd /tmp
wget https://raw.githubusercontent.com/stylersnico/My-arch-packages/master/aurpkglist.txt
sudo pacman -S --needed --noconfirm < aurpkglist.txt
```
