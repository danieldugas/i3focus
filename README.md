# i3focus

An intuitive alt-tab focus switching script.

## Demo

![](demo.gif)

## Install

```
sudo apt install python-pip
pip install --user i3ipc pynput
git clone git@github.com:danieldugas/i3focus.git ~/Code/i3focus
ln -s ~/Code/i3focus/i3focus ~/.i3/i3focus
```

then, in your i3 config file

```
bindsym Mod1+Tab exec --no-startup-id ~/.i3/i3focus
```

## How-to

press `alt`+`tab`

move focus with `i`, `j`, `l`, `,`
toggle focus to/from floating windows with `space`

release `alt`+`tab`
