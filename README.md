# i3-wm-config by rgoomar for v4.3


This is my configuration for the i3 window manager.

It has support for multi-monitor configurations and shows small examples of how that can work. 

Uses Terminal (xfce4 terminal) as the terminal.
It will always open gnome-sound-applet and nm-applet for volume control and network control. 

# Installation Instructions
Install i3 v4.3  
If using Ubuntu or Debian, don't use the one in the aptitude package manager (as of 10-24-2012).  
Follow the instructions on http://i3wm.org/docs/repositories.html  

If using Arch Linux, install from the pacman package manager

`cd ~/.config`  
`git clone git@github.com:rgoomar/i3-wm-config.git i3`

# Keyboard Shortcuts

Mod Key: SUPER key (Mod4)... typically Windows key

## i3 keys
Mod + Shift + q = Reload i3 configuration file  
Mod + Shift + r = Restart i3  
Mod + Shift + e = Exit i3  
Alt + Control + l = Lock screen with background  

## Applications
Mod + Enter = Terminal  
Mod + d = Run dmenu  
Mod + Shift + h = Heroes of Newerth  
Mod + Shift + f = Finch  
Mod + Shift + b = Netbean IDE

## Window Operations
Mod + Shift + c = Kill current window  
Mod + f = Make current window fullscreen  
Mod + Shift + space = Make window floating  

Mod + shift + 1 = Move window to workspace 1  
Mod + shift + 2 = Move window to workspace 2  
Mod + shift + 3 = Move window to workspace 3  
Mod + shift + 4 = Move window to workspace 4  
Mod + shift + 5 = Move window to workspace 5  
Mod + shift + 6 = Move window to workspace 6  
Mod + shift + 7 = Move window to workspace 7  
Mod + shift + 8 = Move window to workspace 8  
Mod + shift + 9 = Move window to workspace 9  
Mod + shift + 0 = Move window to workspace 10  

Mod + r = Resize window  

## Navigation
Mod + j = Focus window to the left  
Mod + k = Focus window down  
Mod + l = Focus window up  
Mod + ; = Focus window to the right  
Mod + t = Change focus between tiling and floating windows  

Mod + 1 = Switch to workspace 1  
Mod + 2 = Switch to workspace 2  
Mod + 3 = Switch to workspace 3  
Mod + 4 = Switch to workspace 4  
Mod + 5 = Switch to workspace 5  
Mod + 6 = Switch to workspace 6  
Mod + 7 = Switch to workspace 7  
Mod + 8 = Switch to workspace 8  
Mod + 9 = Switch to workspace 9  
Mod + 0 = Switch to workspace 10  

## Layouts
Mod + h = Split horizontal layout  
Mod + v = Split vertical layout  
Mod + s = Stacking layout  
Mod + w = Tabbed layout  
Mod + e = Default layout  
Mod + space = Toggle between layouts  

## System Manipulation
Volume Decrease Key (varies on keyboard) / XF86AudioLowerVolume = Lower volume by 5%  
Volume Increase Key (varies on keyboard) / XF86AudioRaiseVolume = Raise volume by 5%  
Volume Mute Key (varies on keyboard) / XF86AudioMute = Mute volume  

## Random Infos
There modifications for notifications using xfce4 notify
Fixes for the netbeans loading screen.
