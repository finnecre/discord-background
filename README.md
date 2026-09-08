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
