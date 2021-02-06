# sway-screen-snatch (sssnatch)
Simple script to mouse a portion of screen and save as timestamped png, for users of wayland / sway.

## Required packages:
sway

slurp

grim

## Install:
`git clone --depth=1 https://github.com/SealedJoy/sway-screen-snatch && cp sway-screen-snatch/sssnatch ~/.local/bin`

(or another location in your $PATH)

## Usage:
`$> sssnatch`

### Note:
if you skip inputting a name for the screenshot, it will be saved to ~/images/screenshots with the datetime as filename.

if you name your screenshot, it will be saved inside of your current working directory.
