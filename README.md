# void-linux-commands
only for personal use

## Steam (с поддержкой 32-битных библиотек)

```sh
sudo xbps-install -S steam libgcc-32bit libstdc++-32bit libdrm-32bit libglvnd-32bit mesa-dri-32bit
```
## Sway
```sh
sudo xbps-install -S sway waybar dbus polkit seatd elogind
```
## Enabling services
```sh
sudo ln -s /etc/sv/dbus /var/service/
sudo ln -s /etc/sv/elogind /var/service/
```
## Остальное
```sh
sudo xbps-install -S git wget telegram-desktop firefox godot make cmake curl vim htop alsa-utils pipewire pipewire-pulse wireplumber xdg-user-dirs unzip openssh rsync networkmanager network-manager-applet
```
