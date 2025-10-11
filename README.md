
# Sikiri

A fork of niri, with Hyprland-style horizontal splitting functionality added.

[日本語版README](README-jp.md)

## Overview

Sikiri arranges windows in a single row on an infinitely extending strip to the right. Opening a new window does not resize existing windows.

**Key Features:**
- Independent strips per monitor: Each monitor has its own window strip. Windows do not spill over onto adjacent monitors.
- Dynamic workspaces: Workspaces are arranged vertically and dynamically. Each monitor has its own set of workspaces, with one empty workspace always available at the bottom.
- Smart workspace preservation: Workspace layouts are preserved as much as possible when monitors are disconnected or reconnected. When a monitor disconnects, its workspaces move to another monitor and return to the original monitor upon reconnection.
- Horizontal splitting: The added horizontal splitting feature assists window movement. niri's original scrollable tiling remains fully usable.
     


## Features

### Inherited from niri

- Scrollable tiling layout
- Dynamic workspaces (GNOME-like)
- "Overview" feature listing workspaces and windows
- Built-in screenshot UI
- Monitor/window screencasting via xdg-desktop-portal-gnome
     - Ability to exclude confidential windows from screencasts
     - Dynamically change the displayed content on the cast destination
- Touchpad and mouse gestures
- Window tabbing
- Configurable layouts (spacing, borders, struts, window size, etc.)
- Gradient borders compatible with Oklab/Oklch
- Animations compatible with custom shaders
- Live configuration reload
- Screen reader support

### Sikiri Custom Features

- Hyprland-style horizontal splitting and moving: Added the ability to split windows horizontally and move them seamlessly.



## Status & Disclaimer

While the base niri is stable for daily use, this fork (Sikiri) is not necessarily stable.

This fork was created by a programming beginner with AI assistance. Stability cannot be guaranteed. **Use at your own risk.**

**Bug Reports:**
If you find a bug, please do not report it to the original niri project. The bug is likely caused by changes made in this fork.

## Inspiration

This project was strongly influenced by its forked source, niri, and traditional tiling window managers like Hyprland.

Special thanks to i3wm for introducing me to the world of window managers, and to niri for providing an excellent foundation.