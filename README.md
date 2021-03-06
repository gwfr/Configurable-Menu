Cinnamon Applet: Configurable Menu Version: v1.6-Beta

Last version release date: 07 december 2014

Contact: lestcape@gmail.com

--------------
![](https://raw.github.com/wiki/lestcape/Configurable-Menu/img/Capture.png)
--------------

Authors:
--------------
- [Lester Carballo Pérez](https://github.com/lestcape)
- [Garibaldo](https://github.com/Garibaldo).

Special thanks to:
--------------
- [Bernard](https://github.com/zagortenay333) (Help adding support to the Cinnamon themes).
- Eliermi Cunha Junior(jpegrande@gmail.com) (Help finding errors, promotion and several more things).
- [mtwebster](https://github.com/mtwebster)  (Help increasing the speed of Configurable Menu in Cinnamon 2.2).


Author of language translation:
--------------
- English(En):       [Garibaldo](https://github.com/Garibaldo) and [Lester Carballo Pérez](https://github.com/lestcape)
- Spanish(Es):       [Lester Carballo Pérez](https://github.com/lestcape)
- Portugese(Pt_Br):  Eliermi Cunha Junior(jpegrande@gmail.com)
- French(Fr):        Dupo(dupop35@yahoo.fr)
- Chinese(Zh_Cn):    Highwind(highwindmx@126.com)
- Czech(Cs_Cz):      Satapouch(http://www.linux-mint-czech.cz/)
- Slovak(sk_SK):     Benji(http://sk.gravatar.com/sawwer/)
- German(de_DE):     Uli(email@kiot.eu)
- Italian(it_IT):    [davcri](https://github.com/davcri)
- Bulgarian(Bg):     Peyu Yovev (spacy01) (spacy00001@gmail.com)

Description
--------------
Configurable Menu is a fork of the Cinnamon stock menu applet. It has much more features and is extremely configurable.
This latest version brings a lot of cool new stuff, like:

- Choose among many different menu layouts.
- Choose different system buttons layouts.
- Define the exact size of the menu (width and height) also with the mouse.
- Show the menu in full screen mode.
- Show/Hide and change the size of some components.
- Two different modes of viewing the menu entrys with multiple columns.
- New drag & drop options.
- Handle removable drives.
- Can Install, uninstall, and search for packages.

A more detail list can be found [here](https://github.com/lestcape/Configurable-Menu/wiki/Some-features).
And much more coming...

Warning:
--------------
After install Configurable Menu 1.1 or higher and if you have installed an older version, please delete the file, /home/USER/.cinnamon/configs/configurableMenu@lestcape  and then restart cinnamon, to allow display correctly the system buttons. This only a thing that need to be done when some key was changed, not always. Sorry for the inconvenients.

Help
--------------
Here you can find interesting information about Configurable Menu.
   - [Layouts](https://github.com/lestcape/Configurable-Menu/wiki/Menu-layouts)
   - [Components](https://github.com/lestcape/Configurable-Menu/wiki/Menu-components)
   - [Settings](https://github.com/lestcape/Configurable-Menu/wiki/Settings)
   - [Cinnamon themes support](https://github.com/lestcape/Configurable-Menu/wiki/Theme-Support)
   - [New languages](https://github.com/lestcape/Configurable-Menu/wiki/Add-new-languages)
   - [Install nightly build](https://github.com/lestcape/Configurable-Menu/wiki/Install-Nightly-Build)

Cinnamon Installer
--------------
Configurable Menu is a applet of the Cinnamon desktop. This desktop can be installed on different Linux distributions and therefore managing the packages that Configurable Menu makes, needs the help of the Cinnamon Installer tool.

The main objective of Cinnamon Installer is that it may be implemented in most of the distributions. However this is far from happening for now. Any help will be well received.

You can found more information about Cinnamon Installer on the [Cinnamon Installer website](https://github.com/lestcape/Cinnamon-Installer).

Change log
--------------
See a complete [Change log](https://github.com/lestcape/Configurable-Menu/wiki/Change-Log).

1.6-Beta
   - Was added Italian language(IT_IT) thanks Davcri.
   - Was added Bulgarian language(Bg) thanks Peyu Yovev.
   - Added support for some sorting methods of search results.
   - Added a limit to the number of packages for not blocking Cinnamon on search.
   - Added support for the new general Cinnamon way of used launchers.
   - Fixed several critical errors and warnings.
   - Added support for Cinnamon 2.3 on general.
   - Configurable Menu not depend any more of the Cinnamon Menu code.
   - Added "open with" on right click in the recent apps.

1.5-Beta
   - Fixed an error that do not allow start the menu.
   - Removed some new warnings in Cinnnamon 2.3.

1.4-Beta
   - Was added German language(DE_DE) thanks Uli.
   - Partially reimplemented the resize options to be more consistent(need more work).
   - Fixed the problem of the menu icon in the cinnamon standard theme.
   - Changed the way of close context menu, to recover the menu size in more cases.
   - Solved the problem of set the size of submenu when cinnamon restart.
   - Allow a more faster start of cinnamon  now, thanks to a change in the handled mode the language files(thanks to [jake-phy](https://github.com/jake-phy)).
   - You can configure the keybinding to open the menu using the settings now, to be compatible with the new cinnamon changes.
   - Used also the super right key by default to open the menu (For conflicts of keybindings visit: https://github.com/linuxmint/Cinnamon/issues/630).

1.3-Beta
   - Was added Slovak language(Sk_SK) thanks Benji.
   - Resolved problem on mini-shake from some locales.
   - Do not allow the open the popupmenu over the Cinnamon panels.
   - Improve the speed of close the popupmenu.
   - Improve the alignment of applications and places in the accessible panel.
   - Add feature to count the number of usages of the applications(only if application is called from the menu).
   - Allows the use of the default Cinnamon packages manager(only if it's available).
   - Allow open the categories on mouse hover or on mouse click.
   - Added "windows" effect on the menu opening and closing.
   - Fixed some bugs on the context menu opening and closing.
   - Fixed some bugs on the menu resize.
   - Horizontal layout, is now called Luz Helena(my girlfriend demanding their rights).
   - Minor corrections.

1.2-Beta
   - Was added kicker Menu layout.
   - Fixed several bugs on Gnome Classic layout.
   - Blocked the opening of applications, when the menu is resized.
   - Allow only show the arrow on the category when selected the category.
   - Improve on the resize option.

1.1-Beta
   - Was added Chinese language(Zh_Cn) thanks Highwind.
   - Was added Czech language(Cs_Cz) thanks Satapouch.
   - Fixed some problems on resize and full screen.
   - Fixed some problem on change the view of Apps/Favorites on the Mint and Windows7 layouts.
   - Improved the speed on some cases, and prevent an error that cause a delay on the menu opening, of about 400 mileseconds.
   - Do not allow mouse release over Apps when the menu opening on mouse pressed.
   - Fixed the translation of the duplicate key Horizontal.
   - Fixed a problem on keyboard navegation on the categories.
   - Fixed the option of delay the changes of the categories, that cause a simultaneously selecting of several categories.
   - Minor corrections.

1.0-Beta
   - The menu was improved to working more faster on cinnamon 2.2.
   - The way to prevent accidental category change when you try to access the applications was redefined.
   - Several internal change to support cinnamon 2.0 and cinnamon 2.2 at the same time with good performance.
   - Horizontal, dragons and gnomenu layous working now a little more faster.
   - Was added French language(Fr) thanks Dupo.
   - In multimonitor system was fixed a bug to displayed the menu.
   - Minor corrections.

0.9-Beta
   - Improved the menu speed.
   - Can Install, uninstall, and search for packages (depend on if Cinnamon Installer can run on your OS).
   - Added web search.
   - Was added support for more languages.
   - Was added Spanish and Portugese(Br).
   - Now you can have a different configuration for each layout.
   - The removable drives are now show in accessible panel and also can be removed.
   - The context menu now have the most usefully options and can be showed also if you have the menu open.
   - The full screen mode was improved, now can be show better in more themes.
   - Now the property "Maximum width of the application entry text" it's really a maximum width and not the width.
   - Added support for the old Clutter.Color API to fix the bug "Clutter.Color.from_string is not a function" when you start the applet.
   - Fixed the bug on mint and windows 7 layouts. This error involves the closure of the menu in the case of the searchEntry do not has a focus.
   - The Menu now can be improved using the css file, of any Cinnamon theme.
   - Removed the hover icon borders, due to allow more compatibility with cinnamon themes.
   - The new layouts of Vampire, Garibaldo, GnoMenu Left, GnoMenu Right, GnoMenu Top, GnoMenu Bottom and Gnome Classic was added.
   - Several visually improvement in different layouts, especially the horizontal.
   - Now you can rename the apps on the accessible panel.
   - Changed the control buttons icons and was added the option to be symbolic or full color.
   - You can swap top and bottom menu panels(also swap the box inside the panels).
   - Control and system buttons now can be symbolic or full color.
   - Allowed remove the search entry.
   - You can have arrows in on the categories.
   - Added the new feature of Cinnamon Menu of Highlight newly installed apps.
   - Added the code to call cinnamon-remove-application to be used if user want, when this feature be included on Cinnamon.
   - Added some fancy effects on opening and closing.

This program is free software:
--------------
You can redistribute it and/or modify it under the terms of the GNU General Public License
as published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.
If not, see http://www.gnu.org/licenses/.

==============
To report bugs, request new features and make suggestions, please visit:
https://github.com/lestcape/Configurable-Menu/issues

You can also send us pull requests:
https://github.com/lestcape/Configurable-Menu/pulls

==============
Thank you very much for using this product.
Lester and Garibaldo.
