# rime-plum-userdata
My rime customization files

<br/>

# Linux setup
- Install [rime](https://github.com/rime/home/wiki/RimeWithIBus) and [plum](https://github.com/rime/plum)

- Install input and clone custom yaml
  ```
  cd plum
  bash rime-install gkovacs/rime-japanese
  cd .config/ibus/rime
  git init
  git remote add origin https://github.com/chungchungdev/rime-plum-userdata.git
  git pull origin master
  ```

<br/>

# Location for the files
* Linux【中州韻】 ```~/.config/ibus/rime/```
* Windows【小狼毫】 ```%APPDATA%\Rime```
* MacOS【鼠鬚管】 ```~/Library/Rime/```
