# Sikiri
A fork of niri. Added Hyprland-style horizontal splitting functionality.

## Overview

Sikiri manages windows by arranging them in a single row on an infinitely extending strip to the right. Opening a new window does not resize existing windows.

     Independent Strips per Monitor: Each monitor has its own window strip. Windows do not “spill over” onto adjacent monitors.
     Dynamic Workspaces: Workspaces are dynamically arranged vertically. Each monitor has its own set of workspaces, with one empty workspace always available at the bottom.
     Smart workspace preservation: Workspace layouts are preserved as much as possible when monitors are disconnected or reconnected. When a monitor disconnects, its workspaces move to another monitor and return to the original monitor upon reconnection.
     Horizontal splitting: The added horizontal splitting feature is solely for assisting window movement. niri's original scrollable tiling remains fully usable.
     

## Features Inherited from niri

### Sikiri inherits all the excellent features of niri.

    Built on scrollable tiling
    Dynamic workspaces like GNOME
    “Overview” feature listing workspaces and windows
    Built-in screenshot UI
    Monitor/window screencasting using xdg-desktop-portal-gnome
     Ability to exclude confidential windows from screencasts
     Functionality to dynamically change the displayed content on the cast destination
     Touchpad and mouse gestures
     Window tabbing
     Configurable layouts (spacing, borders, struts, window size, etc.)
     Gradient borders compatible with Oklab/Oklch
     Animations compatible with custom shaders
     Live configuration reload
     Screen reader support


### Custom Features

     Hyprland-style horizontal splitting/moving: Added the ability to split windows horizontally and move them seamlessly.


## Status

While the base niri boasts stability suitable for daily use, this fork (Sikiri) is not necessarily stable. 

This fork was created by a programming beginner adding custom features with AI assistance. Therefore, stability cannot be guaranteed. Use at your own risk.

Also, if you find a bug, please do not report it to the original niri project. The bug is likely caused by changes made in this fork. 
## Inspiration

This project was created under strong influence from its forked source, niri, and traditional tiling window managers like Hyprland.

Finally, I sincerely thank i3wm for drawing me into the world of window managers, and niri, the forked source, for providing this excellent foundation. 