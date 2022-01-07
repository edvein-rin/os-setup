# OS Setup :gear:

Dual boot: **Manjaro** and **Windows 10**.  
**Windows** is for games.  
**Manjaro** is for everything else.

Setup is semi-automatic. Comes in 2 editions: home and work.  
Both share the whole installation process, but have different additional apps installed.

### Quick Start
First of all follow [Manjaro installation guide](https://github.com/edvein-rin/os-setup/wiki/Manjaro-Installation).  
Then [Windows installation guide](https://github.com/edvein-rin/os-setup/wiki/Windows#installation).  
That's all :)
# Manjaro

## Overview
**OS:** Manjaro 64 bit  
**DE:** XFCE  
**DM:** GDM + gdm-tools-git?  
**WM:** XFCE + devilspie?  
**Compositor:** xfce-compositor  
**Panel:** xfce-panel  
**Navigation:** rofi + power-menu  
**File Manager:** Thunar  
**Terminal:** Kitty  
**Shell:** zsh + p10k  
**Theme:** Gruvbox Material  
**Dot Files Manager:** chezmoi  

## Packages

### Base :computer:
**Pacman:**
chezmoi, kitty, zsh, p10k
make, base-devel, yay, exa, neofetch, tig, github-cli, ncdu,
ttf-jetbrains-mono,
vim, nvim, npm, docker, docker-compose,
Telegram, Discord, qbitTorrent, VLC, Flameshot  
**AUR:** megasync, rofi-power-menu, skypeforlinux-stable-bin, slack-desktop,
spotify, rust, spotify-adblock  
**Snap:** code

### Work Edition :briefcase:
**Pacman:** dbeaver, sqlitebrowser, pgadmin, Opera  
**AUR:** google-chrome, libpdfium-nojs

### Home Edition :desktop_computer: 	
**Pacman:** krita, jupyter-notebook, libreoffice-still

## Installation
1. [Preparation](https://github.com/edvein-rin/os-setup/wiki/Manjaro-Installation#preparation)
2. [OS Installation](https://github.com/edvein-rin/os-setup/wiki/Manjaro-Installation#os-installation)
3. [Configuration](https://github.com/edvein-rin/os-setup/wiki/Manjaro-Installation#configuration)
4. [Customization](https://github.com/edvein-rin/os-setup/wiki/Manjaro-Installation#customization)

# Windows

## Overview
Windows 10 Pro 64 bit. No spying, useless background processes and other trash. Besides that - nothing special.

## Installation
Default Windows install. Nothing is automated yet. Chezmoi + Chocolatey could solve this.

After installing you may need run (at Manjaro) `sudo update-grub` for Windows to appear in grub.
