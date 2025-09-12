# ~/.config

<img width="1920" height="1080" alt="desktop screenshot" src="https://github.com/user-attachments/assets/751da7b7-46d4-494b-bf8f-c1a1d1483d27" />

My personal dotfiles for EndeavourOS. Clean, functional, and built around Hyprland with some custom touches.

## What's Inside

**Window Manager **

- `Hyprland`

**Terminal & Shell**

- `ghostty/` - Terminal setup with CaskaydiaCove Nerd Font and vesper theme, 80% opacity with blur

**Interface & Bars**

- `eww/` - Modular EWW bar with separate calendar and power management widgets
- `waybar/` - Alternative status bar configuration
- `swaync/` - Notification daemon styling to match the overall theme

**Launchers & Tools**

- `wofi` - Application launcher (considering switch to rofi)
- `fuzzel/` - Alternative launcher configuration
- `lazygit/` - Git TUI customization

## Setup Notes

Currently running on a dual monitor setup configuration. The Hyprland config is set up for easy extension when that second monitor arrives.

## Quick Start

Most of these configs expect specific tools to be installed. The Hyprland config auto-starts the essential services:

```
hypridle & hyprlock & hyprpaper & waybar & swaync
```

Terminal font is CaskaydiaCove Nerd Font - make sure it's installed for proper icon rendering.

---

_Built on EndeavourOS • Hyprland • Ghostty • Neovim_
