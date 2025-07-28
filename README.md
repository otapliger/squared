# Valtameri GTK theme

Initially a clone of [EliverLara's Squared gtk-theme](https://github.com/EliverLara/Squared), it aims to be a tailored theme for my systems.

It supports:
- GTK2, GTK3, GTK4
- Gnome
- Cinnamon

### Install

Clone this repository and link the Valtameri folder into yours themes folder:

```sh
mkdir -p ~/.local/share/themes
ln -s /path/to/repository/Valtameri ~/.local/share/themes/
```


### Activate

To activate the theme in Gnome, run the following commands:

```sh
gsettings set org.gnome.desktop.interface gtk-theme "Valtameri"
gsettings set org.gnome.desktop.wm.preferences theme "Valtameri"
```

### Gnome

Gnome requires some extra steps. In order to get it working properly, use [libadwaita-theme-changer](https://github.com/odziom91/libadwaita-theme-changer) to copy the needed folders to the right directories.
