# arch
post installation after archinstall

## packages

```sh
sudo pacman -S wqy-microhei noto-fonts-cjk noto-fonts-emoji ttf-noto-nerd
sudo pacman -S fcitx5-im fcitx5-chinese-addons fcitx5-pinyin-zhwiki
sudo pacman -S sof-firmware
```

```sh
# sudo vim /etc/environment

GTK_IM_MODULE=fcitx
QT_IM_MODULE=fcitx
XMODIFIERS=@im=fcitx
```
