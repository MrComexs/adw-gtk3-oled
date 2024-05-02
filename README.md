This a fork of the adw-gtk3-dark with some css color value changes to make it better for oled users.

> This is still working in progress. it should work mostly fine but might have some small problems.

## Bugs
- text highling can't be seen

## Examples
| APP              | IMAGE                                                                                                               |
|------------------|---------------------------------------------------------------------------------------------------------------------|
| Thunar           |![Thunar](https://github.com/MrComexs/adw-gtk3-oled/assets/57308435/56ef2de9-95c2-49d6-8034-93f321074019)            |
| Gnome Characters |![Gnome-Characters](https://github.com/MrComexs/adw-gtk3-oled/assets/57308435/c8cbb559-1f27-4420-b00d-419d25004c5b)  |
| HandBrake        |![HandBrake](https://github.com/MrComexs/adw-gtk3-oled/assets/57308435/ec756208-8086-44ec-924f-07c958658a61)         |

## Installation 
1. git clone repo
2. mv folder to themes folder

##### System theme folder
if you want all user to **able** to apply this theme than do this one
```bash
mv ./adw-gtk3-oled /usr/share/themes/
```
##### User theme folder
If you only want your user to able able to access the theme than do this step
```bash
mv ./adw-gtk3-oled ~/.themes
```
3. Than change the theme in your DE's theming panel. The theme should be named `adw gtk3 oled`

### Apply theme system wide
make sure you followed this step [system theme folder](#system-theme-folder)
1. open you editor of choice to `/etc/environment`
2. look for `GTK_THEME=` and comment that line
3. add a new line with `GTK_THEME=adw-gtk3-dark`
4. reboot system to apply changes
