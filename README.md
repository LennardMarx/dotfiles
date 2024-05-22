# Linux Dotfiles (i3, alacritty, tmux, nvim)

## Install necessary programs
With package manager:
```
sudo apt install i3 rofi tmux thunar picom
sudo pacman -S i3 rofi tmux thunar picom
```
Via rusts cargo:
```
cargo install i3-autolayout
apt install cmake pkg-config libfreetype6-dev libfontconfig1-dev libxcb-xfixes0-dev libxkbcommon-dev python3
cargo install alacritty
```

## Pull into ~./config folder (maybe somewhere there has to be a git add . in there)
```
git init .
git remote add origin https://github.com/LennardMarx/dotfiles.git
git branch -M main
git pull origin main
```

#### i3
Window manager\
https://i3wm.org/\
Newest version for Ubuntu:\
https://i3wm.org/docs/repositories.html

#### alacritty
Terminal emulator\
https://github.com/alacritty/alacritty

#### tmux 
Terminal multiplexer\
Theme: https://github.com/jimeh/tmux-themepack

#### Thunar
File manager

#### rofi
Configuration for dmenu (dynamic menu, suckless)\
https://github.com/davatorium/rofi

#### i3-autolayout
Splits i3 windows alternating between vertical and horizontal.\
https://github.com/BiagioFesta/i3-autolayout

#### picom
Compositor for X, round corner, transparency, blurring, etc.\
https://github.com/yshui/picom

#### Neovim config
https://github.com/LennardMarx/neovim_config

