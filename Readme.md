# Hyprland config files 

How to install :

```bash
cd ~/.config/hypr
git clone https://github.com/MrStaf/hyprland-config.git .
```
## Features

- AZERTY mapping
- flameshot working with wayland + screen scale != 1

## Custom installs

### Flameshot

- Install `arcolinux-wayland-apps-hook` package 
- Install `flameshot-git` AUR package
- Run `Super + Shift + Print` to take a screen shot

> Note: When updating **screen resolution** in `hyprland.conf` in monitor value, make sure to update 1/scale value in env when calling `flameshot gui` :)

