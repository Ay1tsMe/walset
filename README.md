# Walset Script

![Demo](walset.gif)

This a bash script that uses `pywal` to generate colour schemes and change the wallpaper of the system. I have customised this script in order for it to work on `wayland` applications but you can edit out any program you don't use and replace it with one's you do.

Included is also the `update-theme.sh` for mako if you want colour scheme changes with mako

# Requirements
- `pywal`
- `swww`
- `pywal-discord`
- `mako`
- `waybar`

## Summary
The bash script runs as follows:
1. Gets the `/path/to/image` argument and runs it into `wal`
2. Sets the background with `swww` (Wallpaper manager)
3. Updates betterdiscord colour scheme (`pywal-discord`)
4. Changes `mako` colour scheme (notification manager)
5. Refreshes `waybar` (hotbar)
6. Sends notification 

Depending on your system, you will need to change the script to work for your system. Main principle is to include what program you want to refresh the colour scheme of that `pywal` does not auto-refresh. 

