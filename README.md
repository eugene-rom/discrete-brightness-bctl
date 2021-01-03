# Discrete brightness (brightnessctl based)

Gnome Shell extension to change brightness in discrete steps, unlike default smooth brightness bar in Gnome Shell. For use with old laptops where brightness control doesn't works well when standard method used.

Needs brightnessctl package.

In Debian/Ubuntu install with:

    sudo apt install brightnessctl

Get device name using 'brightnessctl -l'.
Edit extension.js and set DEVICE variable. By default 'acpi_video0' used. 

![screenshot](screenshot.png?raw=true)
