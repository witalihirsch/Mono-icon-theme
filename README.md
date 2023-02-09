# Mono Icons for Gnome
This is a mix of Adwaita symbolic icons and new icons that we made together with my friend. Icons match and don't get out from the style of Adwaita icons.

## Support
<div>
    <a href="https://www.patreon.com/witalihirsch">
        <img src="images/patreon.png" height="60px" >
    </a>
</div>

## Mono Project Preview
<div>
    <a href="https://witalihirsch.github.io/mono.html">
        <img src="images/monoproject.png" height="120px" >
    </a>
</div> 

## Mono icons

<p align="center">
    <img alt="apps" src="images/iconpack.png">
</p>

## Download
Download icons [here.](https://github.com/witalihirsch/Mono-icon-theme/releases)

## Installing
To install icons, place the folder in the `~/.icons` directory and select icons in [Gnome Tweaks](https://gitlab.gnome.org/GNOME/gnome-tweaks). In order for icons to work everywhere, including for flatpak apps, go to the directory where you saved the folder and move the icons folder to `/usr/share/icons`.  
Command:  
```pwsh
sudo cp -r MonoIcons /usr/share/icons
```  
If you don't want to use the default app icons, move the icons from your favorite icon pack to `scalable/apps`.

## Uninstalling
To remove icons, delete the icons folder in `~/.icons` and select the other icons in Gnome Tweaks. Go to `/usr/share/icons` and open a terminal.  
Command:  
```pwsh
sudo rm -r MonoIcons
```