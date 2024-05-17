# Suckless desktop

Patched [dwm](https://dwm.suckless.org/), [dmenu](https://tools.suckless.org/dmenu/) and [st](https://st.suckless.org/).

## Installation

```
$ sudo xbps-install -S base-devel libX11-devel libXft-devel libXinerama-devel
$ git clone https://github.com/aktsbot/suckless
$ cd suckless/dwm
$ make && sudo make install
$ cd ../st
$ make && sudo make install
$ cd ../dmenu
$ make && sudo make install
```

See [my dotfiles](https://github.com/aktsbot/dotfiles/).

![preview](https://www.aktsbot.in/pub/scrots/dwm_suckless_02.png)
