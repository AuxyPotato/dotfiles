# dotfiles
Configuration files for linux customization. Primarily meant for personal use, so expect jank.
The theme is based on the character Elysia from Honkai Impact 3rd.

For compositors, there is a split in x11 and wayland based customization. 
The files for x11 are not maintained and were my first attempt at any customization.
The only scripts currently present are also only relevant to x11 but I expect this will be expanded on later.

The wayland files are more up-to-date as I am currently using hyperland as my daily driver window manager.
Hyprpanel has its own configuration .json file so while it is in the hypr/ directory, this cannot be directly pasted into a .config/

The programs directory is for compositor-agnostic applications. Currently this contains files for discord (vesktop) and spotify (spicetify).
The discord files are customization for system24 and the spotify files for spicetify-text.
These files are mostly CSS, and as the installation of themes has been handled by the applications itself these may not work directly by simply moving the file.
In the first place these are just meant to store settings that can be copy/pasted manually into the GUI editors. 

I am planning to further rework this theme to make it more consistent in colour usage and to streamline this repository so it doesn't look like a mess.
