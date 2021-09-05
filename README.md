# Screenshot

![ ](screenshot.png)

# How it works

The screen is locked with i3lock and then the eww widgets are loaded:

- The calendar widget is made by me. It relies on `vdirsyncer` to pull the calendar events from CalDAV calendar, and on `khal` to obtain the events of the following 3 days.
- The weather widget obtains the weather from openweathermap, the script has been scavenged from other repos [adi1090x/widgets](https://github.com/adi1090x/widgets).
- The player widget is designed to only work with spotify. It obtains the title and artist with `playerctl`, and the album picture is obtained from the web. [Axarva/dotfiles-2.0](https://github.com/Axarva/dotfiles-2.0).

# Features

I set the lockscreen to automatically turn off the screen if there isn't any input in 15 seconds and to suspend if no input is received in 15 minutes. Since I have a dynamical background, when I unlock the background is updated according to the hour of the day. 

# Dependencies

- `i3lock-color`
- `spotify`
- `vdirsyncer`
- `khal`
- `eww`
- `playerctl`
- `xprintidle`

