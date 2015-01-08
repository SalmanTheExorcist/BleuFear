# Bleufear GTK theme

BleuFear is a dark GTK2/GTK3/unity/metacity/xfwm theme with a wild streak of electric blue.  
Original project page: https://github.com/maxfierke/BleuFear

## Install/Usage
-   Copy to `/usr/share/themes/` or `~/.local/share/themes`
-   select it in which ever way you normally do (theme selectro, config file...)

## Suggestions
-   Icon theme: Faenza-Darkest
-   GNOME-shell: [Gnomarch](http://alucryd.deviantart.com/art/Gnome-Shell-GnomArch-245249611)
-   Cinnamon Theme: Minty-Colors
-   To fix text input not rendering dark in Firefox, add this to `~/.mozilla/firefox/$PROFILEDIR/chrome/userContent.css`:

```
input {
-moz-appearance: none !important;
background-color: white;
color: black;
}
textarea {
-moz-appearance: none !important;
background-color: white;
color: black;
}
```

## Links
 * Ubuntu PPA: https://launchpad.net/~m4xm4n/+archive/ubuntu/bleufear
 * ArchLinux AUR package: https://aur.archlinux.org/packages.php?ID=55505


## License
BleuFear is licensed under the GNU GPL version 3.
<http://www.gnu.org/copyleft/gpl.html>

## Authors
* Max Fierke (http://www.maxfierke.com/ - https://github.com/maxfierke/ - https://www.maxfierke.com/projects/)
* Satyajit Sahoo (satya164) - Reponsible for the Evolve theme, of which BleuFear is based on.
* Ivan Kasenkov - Made the metacity, xfwm4, and unity theme that I took from his Adwaita-X-Dark theme.
* Lin Xianyi (@iynaix) - Contributed patches to improve appearence on GNOME 3.8 & GNOME 3.12.
