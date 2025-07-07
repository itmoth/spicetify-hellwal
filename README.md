# Installation

Clone this repository.

```
https://github.com/itmoth/spicetify-hellwal.git
```

Run the following command.
```
spicetify config color_scheme hellwal
```

Move ```hellwal_spicetify.sh``` to wherever you like to put your scripts, and make it executable with ```chmod +x hellwal_spicetify.sh```. This very simple script copies the color.ini file in your cache and copies it to the Comfy theme's folder. 

Move ```color.ini``` to ```~/.config/hellwal/templates/```

If you are using waypaper, in ```~/.config/waypaper/config.ini```, in the post command section, add a command that runs ```hellwal_spicetify.sh```. I have included my waypaper config.ini as an example. 

Finally, change your wallpaper with waypaper so that the command gets ran. 

Re-open the music player app. If your theme doesn't show, you should head to the Settings icon near the top right, click the drop-down menu for the color scheme, and select hellwal. 
