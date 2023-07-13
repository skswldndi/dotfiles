# Dotfiles
Personal dotfiles for macOS systems. 

# Used
## Alfred 5

## Yabai + skhd
- Make sure to disable SID. 

## Übersicht + status bar
- To use status bar, make sure to create symlink with /usr/local/bin/yabai and $which yabai. (ln -s)
- status bar setting;
    - Global
    [x] dark theme
    [x] Floating bar
    [x] No bar background
    [x] Use background color as foreground for widgets
    - Theme: Night Shift Dark (suits well with Mojave Minimal Photo)
    - Process
    [x] Display only current process name
    [x] Show current space mode (BSP, Stack, Float)
    [x] Hide window titles (show only app name for each process)
    - Spaces
    [x] Hide duplicate app icons in same space
    - Widgets
    [x] Process name
    [x] Battery
    [x] Network (with no network name, custom setting)
    ```.wifi .data-widget__inner {display: none;} ```

    [x] Sound
    [x] Microphone
    [x] Date
    [x] Time

# nvim
- https://subicura.com/mac/dev/terminal-apps.html#neovim 
- Spacevim (tmux extension with Nord theme)

## Shell
- Zsh
- Ohmyzsh

## Alarcritty
- fix bug with Applefont blahblah. 

## Tmux
- extension: https://github.com/rothgar/awesome-tmux

## Browser
- Safari with Vimari, which is vim extension
- qutebrowser
