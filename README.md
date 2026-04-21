### Packages Needed:
sway
waybar
swayidle
swaylock
rofi
kitty
btop
blueman
nmtui
nemo
helium-browser
chezmoi

### Icons:
https://store.kde.org/p/1015854
Treepata - High Contrast

### Theme:
https://www.gnome-look.org/p/2010116
BlackAndWhite

### How to use:
```sudo dnf install chezmoi```
```chezmoi init --apply https://github.com/colbycaplan/swayconfig.git```

### How to push code:
```chezmoi git -- add .```
```chezmoi git -- commit -m "<insert message here>"```
```chezmoi git -- push origin main```

### How to pull changes:
```chezmoi update```

### How to edit:
```chezmoi edit ~/.config/sway/config```
```chezmoi edit ~/.config/waybar/config.jsonc```
```chezmoi edit ~/.config/waybar/style.css```
