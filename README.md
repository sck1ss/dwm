# Final DWM
My final dwm source code due to me leaving dwm for [`berry`](https://github.com/jlervin/berry)

It was very fun while it lasted, I enjoyed patching and hacking [`dwm`](https://dwm.suckless.org)

## Dependencies
- `flameshot` screenshotting utility.
- `xlib` usually libx11 on other distros, *required
- `gcc` or llvm but you would need to hack the Makefile. *required for compiling.
- `make` required for install automation, *required but can be done manually.
- `JetBrainsMono Nerd Font` can be changed in config.def.h
- `playerctl` *required for the keybindings that use it.
- `rofi` application launcher *required but can be changed.
- `alacritty` terminal emulator *required but can also be changed.

## Installation
Paste the following snippet into a terminal.
```sh
git clone https://github.com/sck1ss/dwm && cd dwm
sudo make install clean
```
>[!NOTE]
    You can change the prefix of installation using the following snippet.
 ```sh
 make PREFIX=<path> install clean
 ```
* make sure to replace <path> with an actual path or this will not work!!
* changing the PREFIX is not recommended and will give you a hard time to uninstall.
## Uninstallation
cd into the directory you cloned and run the following snippet
```sh
sudo make uninstall clean
```

## Special thanks
- `gur0v` helping me with the fonts.
- `luke smith` inspiring me to change into dwm.
- `r/suckless` guiding me to patching dwm.
