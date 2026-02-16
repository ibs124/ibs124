# Gnome Setup

## Configure key that switches keyboard layout when pressed

```
# Configure a key (Caps Lock) that switches the keyboard layout only when pressed
$ gsettings set org.gnome.desktop.input-sources xkb-options "['grp:caps_switch']"

# Restore effects from the command above 
$ gsettings reset org.gnome.desktop.input-sources xkb-options
```