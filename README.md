Require [Conky](https://github.com/brndnmtthws/conky) is installed in your system.

# Install

```
$ mkdir -p ~/.conky/conky_main_conf && git clone  git@github.com:jeis-aj/conky_main_conf.git ~/.conky/conky_main_conf

$ sed -i -e "s/ngoclb/$(whoami)/g" ~/.conky/conky_main_conf/main.conkyrc
```

Setup `thinkpad-wallpaper.png` as your desktop wallpaper.

# Usage

```
$ conky -q -c ~/.conky/conky_main_conf/main.conkyrc &> /dev/null
```

# Screenshot

- Thinkpad

![](thinkpad-screenshot.gif)

- Manjaro Tree

![](manjaro-tree-screenshot.png)
