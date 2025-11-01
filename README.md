# Black Box Theme(s)
When I begin using Black Box Terminal I noticed that the only way to add new themes was manually downloading a Tilix theme and pasting it in the Black Box schemes folder, so I thought about creating a solution for that, developing an easier way of installing the themes. Hope you like it! 

Note: This is a fork of the project [Tiilix-Themes](https://github.com/storm119/Tilix-Themes), made by [storm119](https://github.com/storm119), I only adapted it to work with Black Box Terminal.

### How to use:
* First, you need to install [Black Box](https://gitlab.gnome.org/raggesilver/blackbox) to use the themes available here. Other terminal wont work...

#### If you installed Black Box with Flatpak:
* Tap the ["Themes-flatpak.md"](Themes-flatpak.md) and pick the one you like and copy/paste the commands below the image preview to your terminal, for example:

```
wget -qO $HOME"/.var/app/com.raggesilver.BlackBox/data/blackbox/schemes/terminix-dark.json" https://git.io/v7QaK
```
* OR manually download the *.json file from a theme you like from the Themes folder and copy the theme to `~/.var/app/com.raggesilver.BlackBox/data/blackbox/schemes/`

* And finally restart Black Box and apply the new theme:


```
Preferences > Terminal > Theme
```

* Preferences > Terminal > Theme

#### If you installed a native Black Box package:
* Tap the ["Themes-native.md"](Themes-native.md) and pick the one you like and copy/paste the commands below the image preview to your terminal, for example:

```
wget -qO $HOME"/.local/share/blackbox/schemes/terminix-dark.json" https://git.io/v7QaK
```
* OR manually download the *.json file from a theme you like from the Themes folder and copy the theme to `~/.local/share/blackbox/schemes/`

* And finally restart Black Box and apply the new theme:

```
Preferences > Terminal > Theme
```

### Uninstall:
* Just delete the theme *.json on the `schemes` folder and you're good to go!


### Screenshot:
* You can see image previews of the themes at ["Themes-flatpak.md"](Themes-flatpak.md) or ["Themes-native.md"](Themes-native.md) before installing... 


# Credits:
* To All the original themes authors
* To [storm119](https://github.com/storm119) the developer of [Tiilix-Themes](https://github.com/storm119/Tilix-Themes) (the project that served as the base for this project) 
* To all the contributors of [Tiilix-Themes](https://github.com/storm119/Tilix-Themes) (listed in it's repository)
* To [Paulo Queiroz aka raggesilver](https://gitlab.gnome.org/raggesilver) the original author of [Black Box](https://gitlab.gnome.org/raggesilver/blackbox)
* To [Gerald Nunn aka gnunn1](https://github.com/gnunn1) the original author of [Tilix](https://github.com/gnunn1/tilix)
* Special thanks to [EliverLara](https://github.com/EliverLara) for the screenies and codes for downloading themes via terminal
