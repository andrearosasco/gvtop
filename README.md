# gvtop
![Alt text](res/light_emerald.png)
![Alt text](res/dark_emerald.png)

## Description
`nvidia-smi` looks sad without colors 😢. If you do not want to be sad, try `gvtop` instead (FDA approved). `gvtop` is a monitoring tool for NVIDIA GPUs with *real* Material You colors. A lot of "Material Design" programs out there are rather "Material *inspired*", in the sense that they use color palettes that resemble but not exactly coincide with official ones. In contrast, `gvtop` uses real Material Design palettes, created by [m3](https://github.com/gvlassis/m3) (frontend for [material-color-utilities
](https://github.com/material-foundation/material-color-utilities)). And like a real Material You application, `gvtop` is adaptable - it reacts to light/dark mode and has multiple (20) [color themes](./res/).

Features:
1) Auto light/dark mode in the terminal via [`CSI?996n`](https://contour-terminal.org/vt-extensions/color-palette-update-notifications/) 
2) 20 bedazzling [color themes](./res/)
3) Zero flickering via [Synchronized Update](https://gitlab.com/gnachman/iterm2/-/wikis/synchronized-updates-spec)
4) Inappropriate compliments when exiting
5) Glanceable usage in terminal title

## Usage
1)  Use a terminal that supports `CSI?996n`, Synchronized Update ([Kitty](https://sw.kovidgoyal.net/kitty/), [WezTerm](https://wezterm.org/), [Ghostty](https://ghostty.org/) etc.), along with a [Nerd Font](https://www.nerdfonts.com/).
2)  Install from GitHub via pip:

        pip install git+https://github.com/gvlassis/gvtop
        
3)  Run:
        
        # Simply
        gvtop
        
        # Change the theme
        GEM=quartz gvtop

