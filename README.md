# Blockbench Themes

This repository hosts community-created [Blockbench](https://blockbench.net) themes that can be directly viewed and equipped in the Theme menu.

To load a theme, go to **File** > **Preferences** > **Theme...**, and click on the theme you would like to use.

For Blockbench 4.0+.

## Submitting themes

You can submit a theme by opening a Pull Request:

* Create your theme in the Blockbench theme editor. Make sure to enter title and author.
* Export your theme as a bbtheme file.
* Add your theme file to the `themes` folder via Pull Request.

**Please note** that submitted themes need to meet a pretty high quality standard because it will appear directly in Blockbench. Themes need to be unique and pleasant to look at.

Learn more about creating custom themes on the [Custom Themes Wiki Page](https://www.blockbench.net/wiki/blockbench/themes).

## Theme template

```js
{
  "name": "Theme Name", // The name of the theme
  "author": "Author Name", // Your name
  "borders": false, // Should the theme enable Blockbench's built in borders
  "main_font": "Font Name", // The main font
  "headline_font": "Font Name", // The font for headings
  "code_font": "Font Name", // The font for code
  "css": "body { filter: invert() }", // Custom CSS for the theme
  "thumbnail": ".theme_preview_window  { filter: invert() }", // Custom CSS for the theme's thumbnail
  "desktop_only": false, // Set the theme to be desktop only
  "colors": { // Colors to replace Blockbench's default colour scheme
    "ui": "#2b2d31",
    "back": "#232428",
    "dark": "#1a1b1e",
    "border": "#1e1f22",
    "selected": "#6d6f78",
    "button": "#4e5058",
    "bright_ui": "#ffffff",
    "accent": "#5865f2",
    "frame": "#1e1f22",
    "text": "#dbdee1",
    "light": "#ffffff",
    "accent_text": "#060607",
    "bright_ui_text": "#060607",
    "subtle_text": "#949ba4",
    "grid": "#4e5058",
    "wireframe": "#6d6f78",
    "checkerboard": "#232428"
  }
}
```