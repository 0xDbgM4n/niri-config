Bước 1: Gỡ bỏ toàn bộ gói của Hyprland

```
sudo pacman -Rns hyprland hyprland-guiutils hyprcursor hyprgraphics hyprlang hyprlock hyprtoolkit hyprutils hyprwire grimblast-git
```

Bước 2: Dọn dẹp các gói liên quan đến KDE/Qt (vì bạn không dùng KDE)

```
sudo pacman -Rns konsole dolphin ark gwenview okular partitionmanager polkit-kde-agent qt5ct qt6ct-kde kvantum kvantum-qt5
```

Bước 3: Gỡ các gói trùng lặp

```
sudo pacman -Rns nodejs npm node-gyp nodejs-nopt semver
yay -Rns noctalia-shell
```