# discord-background

A lightweight CSS theme that lets you use a custom background image in Discord.

It is designed for clients that support custom Discord themes, such as Vencord and BetterDiscord.

The theme keeps Discord's native fonts, colors, and general interface style while adding:

- a custom wallpaper
- transparency so the wallpaper shows through
- support for both Light and Dark mode
- optional multi-column server icons

## Installation

Download:

`custombackground.theme.css`

Then add it to your Discord modification client as a custom theme.

For example, in Vencord, place the file in your themes folder and enable it from the Themes section.

## Customize Your Wallpaper

Open `custombackground.theme.css` in any text editor.

Find the section labeled:

`CUSTOMIZE HERE`

Then find this line:

```css
--wallpaper: url('WALLPAPER-LINK');
```

Replace `WALLPAPER-LINK` with a direct link to your image.

Example:

```css
--wallpaper: url('https://example.com/image.png');
```

For best results, use a direct image URL.

The theme uses:

```css
--wallpaper-size: cover;
```

This automatically scales the image to fill the Discord window without tiling.

## Server Columns

The theme also supports optional multi-column server icons.

Find this line:

```css
--columns: 0;
```

Change `0` to the number of columns you want.

Example:

```css
--columns: 3;
```

If you do not want multiple server columns, leave it at:

```css
--columns: 0;
```

## Light and Dark Mode

This theme supports both Discord Light Mode and Dark Mode.

Use whichever mode works best with your wallpaper.

Light wallpapers will usually look best with Light Mode, while darker wallpapers may look better with Dark Mode.

## Notes

- This theme does not replace Discord's fonts or redesign the interface.
- Popouts, settings, menus, and profile modals remain opaque for readability.
- The main Discord workspace is transparent so your wallpaper can show through.
- Some Discord updates may change internal class names and require small CSS fixes.

## Files

### `custombackground.theme.css`

The main theme file.

### `servercolumns.css`

Handles the optional multi-column server layout.

## Credits

Server column layout based on the original ServerColumns theme by mwittrien.

Theme customization and background implementation by finney.
