# Introduction
Tint2 is my favourite panel. It offer GUI option to customize the configuration, easy to use but extremely customizable.
And lightweight. I use Tint2 in Openbox, Fluxbox, and Xfce.
This repository is  my personal backup of my tint2 collections, but everyone are welcome to use it.
## Preview
## Leve, Raven, Clair, & Triste
![preview-leve](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-leve.jpg) <br />
![preview-raven](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-raven.jpg) <br />
All of them look similar. The only difference is the background colour. 
Leve has semi-transparent white background. Raven has semi tranparent black backround.
Clair has opaque white background. Triste has opaque black background.
All of them has eight colour accent options. So, total 32 themes available.
The now-playing and weather need executor script those are available in my [dotfiles](https://git.io/addydots).
now-playing executor is for mpd music player. <br />

## Liness
![preview-liness](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-liness.jpg) <br />
Just a line shapped workspace indicator. The icons are glued in the wallpaper :stuck_out_tongue: <br />

## Minima
![preview-minima](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-minima.jpg) <br />
Like its name, a minimal tint2 configuration. With underline <br />

## Unleashed
![preview-unleashed](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-unleashed.jpg) <br />
All items in the screenshoot (taskbar, workspace indicator, statusbar, clock, and dot shapped bookmark launcher) are using tint2.
The workspace indicator is hardcoded for four workspace & 1366px screen wide. 
The bookmark launcher will show a tooltip of website name on hover.
I made this when *Tint Button* feature had not been invented.
So I made the buttons using traditional *Tint2 Launcher* which is convoluted.
You need to edit the `*.desktop` files first. <br />

## Launchy
![preview-launchy](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-launchy.jpg) <br />
Just contains Start Menu, shortcut of some apps I frequently use, and some bookmark launcher.
I use Rofi as start menu. The custom script needed is available in my [dotfiles](https://git.io/addydots). <br />

## Blocks
![preview-blocks](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-blocks.jpg) <br />
Just bookmark launcher of website I frequently use. It's autohide, so doesn't waste any screen space. <br />

## Starty
![preview-starty](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-starty.jpg) <br />
The bottom left buttons are (in order) Start Menu, Expose, Screenshoot, and Power Menu.
Start Menu will launch `rofi` with custom configuration (minus colour scheme).
Expose will launch `skippy-xd`.
Screenshoot will launch `scrot` then instantly show the result using `viewnior`.
Power Menu will launch `oblogout`.
Install those packages if You didn't have.

## Popside
![preview-popside](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-popside.jpg) <br />
Simple Startmenu & Taskbar. Search Button will launch `rofi` with custom configuration (minus colour scheme).
Taskbar will only visible if You have any window opened.

## Neon
![preview-neon](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-neon.jpg) <br />
Identical with Popside. Just different colour.

## Uncreative
![preview-minima](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-uncreative.jpg) <br />
Just task buttons <br />

## Zug
![preview-zug](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-zug.jpg) <br />
The top part is Conky and need Bebas Neue font <br />

## Fmaj7
![preview-fmaj7](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-fmaj7.jpg) <br />
Only start menu button for launching rofi & expose button for launching skippy-xd.
Rofia script is available in my dotfiles. Also has alternative config with taskbar.
This panel will autohide. Only visible on hover. <br />

## Carina
![preview-carina](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-carina.jpg) <br />
Need weather executor from my dotfiles. The right part is just iconless & textless taskbar haha <br />

## Repentance
![preview-repentance](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-repentance.jpg) <br />

## Livia
![preview-livia](https://raw.githubusercontent.com/addy-dclxvi/tint2-theme-collections/master/preview-livia.jpg) <br />
Rofi script glued in te tint2 button

## Getting Started & Notes
- You need Tint2 with executor, separator, and buttons support.
If You are on rolling release distro, nothing to worry.
But if You are on Debian, use Backported Tint2 from Bunsenlabs repository.
Or simply build from source.
- The executor & utility scripts are available in my [dotfiles](https://git.io/addydots).
- All of these configuration are built using Tint2Conf GUI.
So probably the code is not very clean.
- Bookmark Launcher is using Firefox. If You are using another Web Browser, just edit the configuration files.
- The icons path is hardcoded to */home/addy/*. Replace addy with your username in the configuration files.
- I always use Noto Sans and Roboto fonts
- Probably couldn't work out of the box :stuck_out_tongue:

## Installation
Simply just clone this repo to your Tint2 configuration folder <br />
`git clone https://github.com/addy-dclxvi/tint2-theme-collections ~/.config/tint2 --depth 1` <br />
Then launch the tint2 with `-c` flag, for example <br />
`tint2 -c ~/.config/tint2/blocks/blocks.tint2rc &` <br />
Add it to your autostart to make your life easier :wink:

## Credits
[BunsenLabs Forum](https://forums.bunsenlabs.org/viewtopic.php?id=254), I learn so much there.
[ARCHLabs Github](https://github.com/ARCHLabs/Archlabs-Tint2-Themes), one of my main resouces for learning.
[Anachron i3blocks](https://github.com/Anachron/i3blocks), I try to execute an i3block script using tint2 executor, without any expectation it will work.
But ridiculously it works! So I slightly modify it to fit into my tint2 themes.

## License
GPL of course. Feel free to modify and share this theme.

## Other Link
[Deviant Art](http://addy-dclxvi.deviantart.com/)

