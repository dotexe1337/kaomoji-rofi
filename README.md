# Kaomoji Rofi (dotexe fork)

Rofi script for typing kaomojis. Types kaomojis and copies them into your clipboard.

Originally by Ceda EI, forked by dotexe.
Modified to split on spaces so you only get the Kaomojis copied to clipboard, and not the spaces and names of them.

## Requirements

+ `rofi`
+ `xdotool`
+ `xclip`

## Installation

+ `git clone https://github.com/original-dotexe/kaomoji-rofi`
+ Add a keybinding to run `/path/where/you/cloned/kaomoji-rofi/kaomoji.sh`

## Configuration

All options passed to kaomoji.sh are passed to rofi. The screenshot has been
taken with the following command. `kaomoji.sh -config config -theme some_theme.rasi`
