# CosmosCost Dark - Ghostty Theme

A dark theme for the [Ghostty terminal](https://ghostty.org/) based on the CosmosCost Dark VSCode theme.

## Table of Contents

- [Preview](#preview)
- [Installation](#installation)
- [Color Palette](#color-palette)
- [Usage](#usage)

## Preview

This theme features a dark blue-slate background with vibrant accent colors including purple, coral, pink, and cyan.

### Color Scheme

- **Background**: Deep slate blue (`#0f172a`)
- **Foreground**: Light gray (`#e2e8f0`)
- **Cursor**: Purple (`#a78bfa`)
- **Selection**: Blue with transparency (`#3b82f6`)

## Installation

1. Copy the `cosmoscost-dark.conf` file to your Ghostty themes directory:

```bash
# On macOS/Linux
mkdir -p ~/.config/ghostty/themes
cp cosmoscost-dark.conf ~/.config/ghostty/themes/
```

2. Add the theme to your Ghostty configuration (`~/.config/ghostty/config`):

```conf
theme = cosmoscost-dark
```

Or specify the full path:

```conf
theme = /path/to/cosmoscost-dark.conf
```

## Color Palette

The theme uses the following ANSI color palette:

| Color          | Normal    | Bright    |
|----------------|-----------|-----------|
| Black          | `#0f172a` | `#334155` |
| Red            | `#ef4444` | `#ef4444` |
| Green          | `#f59e6d` | `#f59e6d` |
| Yellow         | `#f7b890` | `#f7b890` |
| Blue           | `#a78bfa` | `#a78bfa` |
| Magenta        | `#ec4899` | `#ec4899` |
| Cyan           | `#06b6d4` | `#06b6d4` |
| White          | `#e2e8f0` | `#ededed` |

### Additional Colors

- **Cursor Color**: `#a78bfa` (purple)
- **Cursor Text**: `#0f172a` (dark slate)
- **Selection Background**: `#3b82f6` (blue)
- **Selection Foreground**: `#ededed` (off-white)
- **Split Divider**: `#334155` (slate gray)

## Usage

Once installed, you can activate the theme by either:

1. Setting it in your Ghostty config file as shown in the installation section
2. Using the Ghostty settings UI to select the theme

The theme is designed to work well with the CosmosCost Dark VSCode theme for a cohesive development experience across your editor and terminal.

## Credits

Based on the [CosmosCost Dark VSCode theme](https://github.com/jandro/vscode-theme).
