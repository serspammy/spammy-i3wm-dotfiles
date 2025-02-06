# spammy-i3wm-dotfiles
![image](https://github.com/user-attachments/assets/67cd62b7-6ed7-4018-bf95-dffde9b42bac)



my i3 window manager configuration files. am i doing this right?

required packages: i3, jq, nitrogen, picom, polybar, rofi, brightnessctl, alacritty(or any terminal emulator that works ith nerdfonts)

nerd fonts used: UbuntuMono, SauceCodePro, Iovseka

custom polybar module(s): weather (https://github.com/Strix007/polybar-getweather), power and launcher (https://github.com/adi1090x/rofi)

rofi theme: https://github.com/adi1090x/rofi

i3lock-color (i3lock fork for customization): https://github.com/Raymo111/i3lock-color

picom version v12.5: https://github.com/yshui/picom


notes:
1. add yourself to the `video` group for brightnessctl to work without `sudo` (there's probably a more graceful way of doing this but this is what works for me)
2. the polybar weather module is not provided, follow the instructions given in https://github.com/Strix007/polybar-getweather (or just use one that doesn't require an openweather account lol i should've tried looking for that myself)
3. press $mod+t to set a random wallpaper, they're located inside `~/.config/nitrogen/wallpapers`
4. i wanted to have rofi fly in from the left as a sidebar but i couldn't get the window rule to work. genereally picom's new window rules make my head hurt so i just don't use them 💀
5. the rofi powermenu's text will probably "break" if your uptime is long enough
