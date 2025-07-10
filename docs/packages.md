# packages
a documented list of packages used for the final setup. *base, system, and other irrelevant packages are excluded.*

## notes
- AUR packages, if any, are distinguished by an *asterisk (\*)* at each bullet point. for such packages, an AUR helper must be installed in your system, such as [paru](https://github.com/Morganamilo/paru) or [yay](https://github.com/Jguer/yay)

---

## uncategorized packages
*recently installed packages yet to be categorized or documented*

```
nothing here, yet!
```

## desktop environment

```
hyprland grim mako waybar wl-clipboard xdg-desktop-portal-hyprland
```

- **hyprland** - our beloved wayland compositor
- **grim** - screenshot utility
- **mako** - notification daemon
- **waybar** - status bar
- **wl-clipboard** - command line copy/paste utility
- **xdg-desktop-portal-hyprland** - xdg-desktop-portal backend for Hyprland

## fonts & themes

```
apple_cursor noto-fonts noto-fonts-cjk papirus-icon-theme plymouth ttf-cascadia-mono-nerd ttf-twemoji
```

- **apple_cursor**\* - macOS cursor theme
- **noto-fonts-cjk** - fallback font for chinese, japanese, and korean characters
- **plymouth** - boot splash screen
- **ttf-cascadia-mono-nerd** - cascadia mono font, patched to include nerd font glyphs
- **ttf-twemoji**\* - emoji font originally built by twitter

## system & utilities

```
nano git networkmanager power-profiles-daemon zsh
```

- **nano** - terminal-based text editor
- **git** - version control system, used for cloning and managing git repos
- **networkmanager** - as the name suggests, the network manager
- **power-profiles-daemon** - utility for switching and managing power profiles
- **zsh** - powerful, customizable shell. used as a bash replacement

## applications

for a detailed description of apps, including flatpak packages, see [`docs/applications.md`](TODO)
