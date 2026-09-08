# discord-background

lightweight css theme that lets you use a custom background image in discord.

designed for clients that support custom discord themes, such as vencord and betterdiscord.

the theme keeps discord's native fonts, colors, and general interface style while adding:

- a custom wallpaper
- transparency so the wallpaper shows through
- support for both light and dark mode
- optional multi-column server icons

## installation

download:

`custombackground.theme.css`

then add it to your discord modification client as a custom theme.

for example, in vencord, place the file in your themes folder and enable it from the *themes* settings.

## customise your wallpaper

open `custombackground.theme.css` in any text editor.

find the section labeled:

`CUSTOMISE HERE`

then find this line:

```css
--wallpaper: url('WALLPAPER-LINK');
```

replace `WALLPAPER-LINK` with a direct link to your image.

example:

```css
--wallpaper: url('https://example.com/image.png');
```

for best results, use a direct image url.

the theme uses:

```css
--wallpaper-size: cover;
```

to automatically scales the image to fill the discord window without tiling.

## server columns

the theme also supports optional multi-column server icons.

find this line:

```css
--columns: 0;
```

change `0` to the number of columns you want.

example:

```css
--columns: 3;
```

if you do not want multiple server columns, leave it as is.

## light and dark mode

use whichever mode works best with your wallpaper. both are supported.

light wallpapers will usually look best with light mode, while darker wallpapers may look better with dark mode.

## notes

- this theme does not replace discord's fonts or redesign the interface.
- popouts, settings, menus, and profile modals remain opaque for readability.
- the main discord workspace is transparent so your wallpaper can show through.
- some discord updates may change internal class names and require small css fixes.

## credits

server column layout based on the original ServerColumns theme by [mwittrien](https://github.com/mwittrien).

theme customization and background implementation by finnecre.
