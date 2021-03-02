# Discrete brightness (brightnessctl based)

Gnome Shell extension to change brightness in discrete steps, unlike default smooth brightness bar in Gnome Shell. This variant for use with old laptops where brightness control doesn't works well when standard method used.

Needs brightnessctl package.

In Debian/Ubuntu install with:

    sudo apt install --install-recommends brightnessctl

Add user to `video` group.
Get device list using `brightnessctl -l`.
Edit extension.js and set DEVICE variable. By default `acpi_video0` used. 

![screenshot](screenshot.png?raw=true)
