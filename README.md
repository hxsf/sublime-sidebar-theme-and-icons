# Sublime Text sidebar icons and theme

> 1. The collection of file type icons for Sublime Text editor.
> 2. The black theme sidebar.

Please note that icons included in this repository are best suited with a dark background but you can [customize](#customizing-the-icons) them.


## Installation

The purpose of this collection is to override the default icons that come with [themes]. Unfortunately, this prevents from creating a package that could be installed via [Package Control].

To install the icons you'll have to clone this repo to your [Packages] folder and rename the folder's name to match your current theme's package (folder) name, like so:

    git clone https://github.com/hxsf/sublime-sidebar-theme-and-icons.git [folder name]

For example, I use Predawn theme, so my `[folder name]` is `Predawn`.

Other themes that I tested and folder name you should use:

* Sublime's default theme - `Theme - Default`,
* [Afterglow] - `Theme - Afterglow`,
* [Aprosopo] - `Theme - Aprosopo`,
* [Cobalt2] - `Theme - Cobalt2`,
* [Coffee] - `Theme - Coffee`,
* [Cyanide] - `Theme - Cyanide`,
* [Flatgrammer] - `Theme - Flatgrammer`,
* [Fox] - `Theme - Fox`,
* [Material] - `Material Theme`,
* [Predawn] - `Predawn`,
* [SoDaReloaded] - `Theme - SoDaReloaded`,
* ...and so on.


## Customizing the icons

In `src` you'll find `file_type_icons.psd` file which contains all the icons. You can modify the however you want, all you need is Photoshop CS6 or later (but it might work in older versions).

Also there's simple Photoshop script `export-icons.jsx` that looks for layer groups with names ending with '.png' and exports them to `../icons` folder. You can run it by clicking File → Scripts → Browse... and selecting the script.


## Further notes

For managing themes I suggest the [Themr] package, it makes changing themes and customizing them much easier.

If you want me to add some icons or have any suggestions, please add [new issue](https://github.com/hxsf/sublime-sidebar-theme-and-icons.git/issues/new).
Feel free to make new icons and send the full `file_type_icons.psd` if you want to share.

Most of the icons I took from the great [devicons] and [devicon] sets, some are slightly modified and some are I drew myself.

## License

Under MIT Licence.

*I do not own rights for any of the logos or other images used, they belong to the rightful owners.*

Thanks for [mrliptontea / sublime-text-sidebar-icons](https://github.com/mrliptontea/sublime-text-sidebar-icons)


[Package Control]: https://packagecontrol.io/
[Packages]: http://docs.sublimetext.info/en/latest/basic_concepts.html#the-packages-directory
[Themr]: https://packagecontrol.io/packages/Themr
[themes]: https://packagecontrol.io/browse/labels/theme
[Afterglow]: https://packagecontrol.io/packages/Theme%20-%20Afterglow
[Aprosopo]: https://packagecontrol.io/packages/Theme%20-%20Aprosopo
[Cobalt2]: https://packagecontrol.io/packages/Theme%20-%20Cobalt2
[Coffee]: https://packagecontrol.io/packages/Theme%20-%20Coffee
[Cyanide]: https://packagecontrol.io/packages/Theme%20-%20Cyanide
[Flatgrammer]: https://packagecontrol.io/packages/Theme%20-%20Flatgrammer
[Fox]: https://packagecontrol.io/packages/Theme%20-%20Fox
[Material]: https://packagecontrol.io/packages/Material%20Theme
[Predawn]: https://packagecontrol.io/packages/Predawn
[SoDaReloaded]: https://packagecontrol.io/packages/Theme%20-%20SoDaReloaded
[devicons]: http://vorillaz.github.io/devicons/
[devicon]: http://devicon.fr/