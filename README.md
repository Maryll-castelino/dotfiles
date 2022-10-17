# DOTFILES
My config files for awesomewm

- WM : AwesomeWM
- Terminal : Alacritty
- Theme : Nord + Dracula
- GTK Theme : Dracula
- vscode theme : One Dark Pro
- compositor : [jonaburg-picom](https://github.com/jonaburg/picom)
- Wallpaper : [here](https://github.com/Maryll-castelino/Wallpapers/blob/master/arch-dracula.png)

## Screenshots
![home](screenshots/home.png)
![editor](screenshots/editor.png)
![terminals](screenshots/terminals.png)

## Usage:

### Dependancies : 
- Nerd Font for the tag icons.
- Pactl for volume control
- xbacklight for brightness control

### Installation
1. cd into your .config folder
```
cd .config
```
2. backup your existing configuration
```
mv awesome myawesome-backup
```
3. clone this repository along with the submodules
```
git clone --recurse-submodules -j8 https://github.com/Maryll-castelino/dotfiles.git awesome
```
4. restart awesome

Report any issues you face and I'll be happy to address them😇
