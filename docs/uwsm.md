# uwsm

`uwsm` stands for universal wayland session manager. it is used to properly launch hyprland from our display manager (GDM). it is the **officially recommended** way to start Hyprland on systemd-based distros like Arch Linux. it helps manage our Hyprland session in a clean way for a more stable experience.

`uwsm` does **not** replace our display manager. rather, it works alongside it, as our display manager launches our uwsm-managed Hyprland session.

## usage

once `uwsm` has been installed, assuming the display manager has been setup, simply launch Hyprland through the `hyprland (uwsm-managed)` desktop entry.

## see also
- [Systemd startup - Hyprland Wiki](https://wiki.hypr.land/Useful-Utilities/Systemd-start/#uwsm)
- [Vladimir-csp/uwsm](https://github.com/Vladimir-csp/uwsm)
