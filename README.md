# Dark+ V2 Italic

A splash of italics added to the new and experimental Dark+ V2 theme added in Visual Studio Code
1.75 in January 2023. Make your script fonts shine! This theme is inspired by [Dark++
Italic](https://marketplace.visualstudio.com/items?itemName=idbartosz.darkpp-italic), a minimal
modification of the default theme to add italics to highlight script fonts.

The screenshot below this theme with the "Caskaydia Code" remix of Cascadia Code:

![A screenshot of the theme in four languages in quadrants. From left to right in the top row: TypeScript/React and Go; in the bottom row: Python and Rust](./docs/theme-example.png)

## Enabling Script Italics

I recommend [Microsoft's Cascadia Code](https://github.com/microsoft/cascadia-code) with script italics, patched with [Nerd Fonts](https://www.nerdfonts.com/) to add symbols. This font can be found in a fork of Nerd Fonts as "Caskaydia Code" https://github.com/AaronFriel/nerd-fonts/releases.

The set of font ligature options enabled is enabled by setting `editor.fontLigatures` in settings to include stylistic set 1 (`'ss01'`). Additional options are available, see the [Cascadia Code repository](See: https://github.com/microsoft/cascadia-code) for more.

The settings for this screenshot were:

```json
  "editor.fontFamily": "'CaskaydiaCove Nerd Font', 'Consolas', 'Courier New', monospace",
  "editor.fontLigatures": "'calt', 'ss01', 'ss04', 'ss05', 'ss06', 'salt', 'zero', 'onum'",
  "editor.fontSize": 14,
  "editor.fontWeight": "400",
```
