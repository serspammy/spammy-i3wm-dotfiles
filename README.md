# spammy-xfi3-dotfiles
![image](https://github.com/user-attachments/assets/8f3c3659-7e90-425c-946e-1778b34bb5fb)
### a mix of xfce and i3wm
basic setup instructions: 

### stuff to install
- i3 (duh)
- xfce4 (desktop environment)
- nitrogen (wallpaper)
- picom (EYE CANDY 🤑🤑🤑🤑)

### non-essentials for this rice:
- polybar (replaced by xfce4-panel)
- rofi (replaced by xfce4-appfinder)
- dunst (replaced by xfce4-notifyd)
- alacritty (or some other terminal that'll work with nerdfonts)
  - a nerd font (duh)
- ~~[i3lock-color](https://github.com/Raymo111/i3lock-color) (replaced by xflock4/xfce4-screensaver, config exists but i never got it to work on startup. i don't know why it wouldn't work) (you probably need to build this from source btw unless you're on arch or whatever)~~
- i3lock-fancy (just use this one tbh)

#### other things in screenshots:
- qimgv (image viewer with no menubar or whatever)
- cmatrix
- cava
- cbonsai
- pipes.sh
-----

### nerd fonts used:
- Ubuntu Medium (i3 titlebars, if you want them)
- JetbrainsMono (terminal font)

### rofi theme: https://github.com/adi1090x/rofi

-----
## notes:

1. `$mod+t` to randomly switch wallpapers! walls should be located in `~/Pictures/wallpapers`
2. my `picom.conf` uses the old config style because windows rules make my head hurt. sorry if you don't like badly-written configuration
3. toggling resize mode will send a notification. not having an indicator when using a bar other than i3bar always bothered me
4. multiple i3 utilities (i.e. dmenu/rofi, dunst, i3bar) have been replaced with xfce4 tools, but they have old existing configurations you can use
5. you can use `xfce4-session-settings` to manage startup programs, but sometimes it doesn't work from my experience, so doing so using the i3 configuration is a working alternative
