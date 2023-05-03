# arch
post installation after archinstall

## packages

```sh
sudo pacman -S wqy-microhei noto-fonts-cjk noto-fonts-emoji ttf-noto-nerd
sudo pacman -S fcitx5-im fcitx5-chinese-addons fcitx5-pinyin-zhwiki
sudo pacman -S zsh zsh-autosuggestions zsh-syntax-highlighting zsh-theme-powerlevel10k
sudo pacman -S sof-firmware
```

```sh
# sudo vim /etc/environment

GTK_IM_MODULE=fcitx
QT_IM_MODULE=fcitx
XMODIFIERS=@im=fcitx
```

```sh
# init zsh

zsh

# vim ~/.zshrc

source /usr/share/zsh/plugins/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
source /usr/share/zsh/plugins/zsh-autosuggestions/zsh-autosuggestions.zsh
source /usr/share/zsh-theme-powerlevel10k/powerlevel10k.zsh-theme

# set default shell

chsh -s /usr/bin/zsh
```
