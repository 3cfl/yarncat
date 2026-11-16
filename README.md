# yarncat

a little cat that rolls around in your terminal

![yarncat](yarncat.gif)

## setup

on arch:

```sh
git clone https://github.com/3cfl/yarncat
cd yarncat/arch && makepkg -si
```

anywhere else (you just need python 3):

```sh
curl -Lo ~/.local/bin/yarncat https://raw.githubusercontent.com/3cfl/yarncat/main/yarncat
chmod +x ~/.local/bin/yarncat
```

on windows (also needs python 3):

```
curl -o yarncat.py https://raw.githubusercontent.com/3cfl/yarncat/main/yarncat
py yarncat.py
```

run `yarncat` (or `py yarncat.py` on windows). press any key when you're done watching.
