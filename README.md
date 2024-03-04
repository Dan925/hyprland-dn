# Hyprland setup

## Requirements
- A working Arch Linux system/OR similar with:
    - NetworkManager, BluetoothManager, Pulseaudio, and whatever package manager setup
- An AUR helper like `paru` (forgot why but good to have anyways)
## Installation
- Run:
```
pacman -S hyprland swaylock-effects swayidle kitty wofi waybar dunst pipewire wireplumber polkit-kde-agent qt5-wayland qt6-wayland xdg-desktop-portal-hyprland `
```
- Copy the `hyprland.conf` into `$HOME/.config/hypr/`
- Now `Hyprland` should be in the sys path and running `Hyprland` should launch the window manager

