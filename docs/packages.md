# packages
a documented list of packages used for the final setup. *base, system, and other irrelevant packages are excluded.*

## notes
- AUR packages, if any, are distinguished by <sup>AUR</sup> at each bullet point. for such packages, an AUR helper must be installed in your system, such as [paru](https://github.com/Morganamilo/paru) or [yay](https://github.com/Jguer/yay)

---

## uncategorized packages
*recently installed packages yet to be categorized or documented*

> *nothing here yet...*

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

- **apple_cursor**<sup>AUR</sup> - macOS cursor theme
- **noto-fonts-cjk** - fallback font for chinese, japanese, and korean characters
- **plymouth** - boot splash screen
- **ttf-cascadia-mono-nerd** - cascadia mono font, patched to include nerd font glyphs
- **ttf-twemoji**<sup>AUR</sup> - emoji font originally built by twitter

## system & utilities

```
flatpak git networkmanager power-profiles-daemon zsh uwsm
```

- **flatpak** - sandboxed app distribution system
- **git** - version control system, used for cloning and managing git repos
- **networkmanager** - as the name suggests, the network manager
- **power-profiles-daemon** - utility for switching and managing power profiles
- **zsh** - powerful, customizable shell. used as a bash replacement
- **uwsm** - universal wayland session manager, see [`/docs/uwsm.md`](/docs/uwsm.md)

## applications

```
baobab gnome-disk-utility gnome-software libre-menu-editor loupe nano nautilus vesktop-bin visual-studio-code-bin
```

- **baobab** - disk usage analyzer
- **gnome-disk-utility** - utility for managing storage devices and media
- **gnome-software** - used as a gui for flatpak
- **libre-menu-editor**<sup>AUR</sup> - menu editor for managing .desktop files
- **loupe** - image viewer
- **nano** - terminal-based text editor
- **nautilus** - file manager
- **vesktop-bin**<sup>AUR</sup> - third-party discord client w/ vencord and tweaks
- **visual-studio-code-bin**<sup>AUR</sup> - microsoft's propietary vscode release

*for a more detailed breakdown of the apps i use, including flatpak packages, see [`docs/applications.md`](/docs/applications.md)*
