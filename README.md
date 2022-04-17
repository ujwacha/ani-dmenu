# ani-dmenu
a dmenu fork of ani-cli with dmenu , everything is made intutive: works on GNU/Linux and BSD
have fun , my fellow weebs

# dependencies
dmenu , sed , grep , mpv , curl , awk , tail

# how to install
clone the repo and go inside the ani-dmenu dir
```bash
git clone https://github.com/UjwAcha/ani-dmenu.git && cd ani-dmenu
```
make the script executable
```bash
chmod +x ani-dmenu
```
copy the script to your bin
```bash
cp ani-dmenu /usr/local/bin/ani-dmenu
```
alternatively you can symlink it, that way you can use git pull to keep the script updated (this is optional)
```bash
ln -s <path to ani-dmenu dir>/ani-dmenu /usr/local/bin/dmenu
```

# how to use
```bash
ani-dmenu
```
