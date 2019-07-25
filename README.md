```
┏┓ ╻  ┏━┓┏━┓╻ ╻┏━╸   ┏┳┓┏━┓┏━╸╻┏━╸╻┏ 
┣┻┓┃  ┣━┫┃┓┃┃ ┃┣╸    ┃┃┃┣━┫┃╺┓┃┃  ┣┻┓
┗━┛┗━╸╹ ╹┗┻┛┗━┛┗━╸   ╹ ╹╹ ╹┗━┛╹┗━╸╹ ╹
a low-contrast vim colorscheme with blue and red highlights
by xero harrison (http://xero.nu) and modified by 高明俊
```

![](https://raw.githubusercontent.com/daniel-simon-gonzalez/blaquemagick.vim/master/screenshots/preview_python.png)
![](https://raw.githubusercontent.com/daniel-simon-gonzalez/blaquemagick.vim/master/screenshots/preview_haskell.png)
![](https://raw.githubusercontent.com/daniel-simon-gonzalez/blaquemagick.vim/master/screenshots/preview_cpp.png)
![](https://raw.githubusercontent.com/daniel-simon-gonzalez/blaquemagick.vim/master/screenshots/preview_r.png)

# install

### manually
copy the `colors/blaquemagick.vim` file in this repo to your `~/.vim/colors` directory (create it if it does not exist).

### package manager
add the repo url via your favorite vim package manager. e.g for vundle: `Plugin 'daniel-simon-gonzalez/blaquemagick.vim'` 

# use
then in your `~/.vimrc` or `~/.config/nvim/init.vim` add `colorscheme blaquemagick` and make sure `:syntax on` is set

*note: if installing via plugin, you must set the colorscheme variable after including the plugin in your config file.*

# terminal colors
blaquemagick is also available as a colorscheme for [Xresources](https://github.com/daniel-simon-gonzalez/blaquemagick.vim/blob/master/terminals/blaquemagick.Xcolors) and [OS X](https://github.com/daniel-simon-gonzalez/blaquemagick.vim/blob/master/terminals/blaquemagick.terminal) terminals.
```
--------------------------------------|-----------------------------------------
|   BASIC         HEX                 |     BASIC         HEX                  |
--------------------------------------|-----------------------------------------
|   Foreground    #d7d7d7             |     Text          #585858              |
|   Background    #000000             |     Bold          #585858              |
|   Links         #005cbb             |     Selection     #5F8787              |
--------------------------------------|-----------------------------------------
|
--------------------------------------|-----------------------------------------
|   CURSOR         HEX                |                                        |
--------------------------------------|-----------------------------------------
|   CursorColor   #90110F             |                                        |
|   CursorText    #000000             |                                        |
--------------------------------------|-----------------------------------------
|
--------------------------------------|-----------------------------------------
|   NORMAL        HEX          XTERM  |      BRIGHT        HEX          XTERM  |
--------------------------------------|-----------------------------------------
|   Black         #222222      0      |      brBlack       #222222      8      |
|   Red           #5f8787      1      |      brRed         #5f8787      9      |
|   Green         #87AF5F      2      |      brGreen       #87AF5F      10     |
|   Yellow        #87875f      3      |      brYellow      #87875f      11     |
|   Blue          #870000      4      |      brBlue        #870000      12     |
|   Magenta       #4B5F69      5      |      brMagenta     #4B5F69      13     |
|   Cyan          #777777      6      |      brCyan        #777777      14     |
|   White         #c1c1c1      7      |      brWhite       #c1c1c1      15     |
--------------------------------------|-----------------------------------------
```
