# rime-plum-userdata
My rime customization files

<br/>

# Ubuntu setup
1. Install [rime](https://github.com/rime/home/wiki/RimeWithIBus) 
   ```
   sudo apt install ibus-rime
   ```
2. Install [plum](https://github.com/rime/plum)
   ```
   curl -fsSL https://raw.githubusercontent.com/rime/plum/master/rime-install | bash -s -- :preset
   ```
4. Install Japanese input
   ```
   cd plum
   
   # ibus
   bash rime-install gkovacs/rime-japanese

   # fcitx5
   rime_frontend=fcitx5-rime bash rime-install gkovacs/rime-japanese
   ```
5. Clone custom yaml
   ```
   # ibus
   cd; cd .config/ibus/rime
   # fcitx5
   cd; cd ~/.local/share/fcitx5/rime
   
   git init
   git remote add origin https://github.com/chungchungdev/rime-plum-userdata.git
   git pull origin master
   ```
6. Reboot
7. Add rime in Settings -> Keyboard -> Input source
8. Depoly

<br/>

# Location for the files
* Linux【中州韻】 ```~/.config/ibus/rime/```/```~/.local/share/fcitx5/rime/```
* Windows【小狼毫】 ```%APPDATA%\Rime```
* MacOS【鼠鬚管】 ```~/Library/Rime/```
