# Debian 12 XFCE4 Set Up

## OS Themes
Copy Your themes to:
```
/usr/share/themes
```

## Icon Themes:
Copy your icons to:
```
/usr/share/icons
```
Update Icons Cache
```
sudo gtk-update-icon-cache /usr/share/icons/*
```

## Wallpapers:
Copy the wallpapers to:
```
/usr/share/backgrounds
```

## XFCE4 Terminal themes:
https://github.com/catppuccin/xfce4-terminal
/usr/share/xfce4/terminal/colorschemes

## Add Fonts:
Copy fonts to:
```
sudo cp -r JetBrainsMono/ /usr/share/fonts/truetype/
```
Update Cache:
```
fc-cache /usr/share/fonts
```
## XFCE4 Mousepad theme
Copy theme to:
```
sudo cp dracula.xml /usr/share/gtksourceview-3.0/styles/
sudo cp dracula.xml /usr/share/gtksourceview-4/styles/
```
## lightdm-gtk
Copy config file to:
```
/etc/lightdm/
```
## rofi
Copy config.rasi to:
```
~/.config/rofi
```
Set up keyboard shortcut to run:
```
rofi -show run
```
## Apt Software
```
build-essential
git
git-lfs
vim
tmux
curl
tcpdump
wireshark
zsh
rofi
```



