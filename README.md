# Terafox for Omarchy

A dark teal theme for [Omarchy](https://omarchy.org/) v4 (Quattro) based on the [Terafox](https://github.com/EdenEast/nightfox.nvim) colorscheme from the Nightfox family.

![Terafox theme preview](preview.png)

## Palette

| Role       | Color                                                        |
|------------|--------------------------------------------------------------|
| Background | ![#152528](https://placehold.co/12x12/152528/152528) `#152528` |
| Foreground | ![#e6eaea](https://placehold.co/12x12/e6eaea/e6eaea) `#e6eaea` |
| Red        | ![#e85c51](https://placehold.co/12x12/e85c51/e85c51) `#e85c51` |
| Green      | ![#7aa4a1](https://placehold.co/12x12/7aa4a1/7aa4a1) `#7aa4a1` |
| Blue       | ![#5a93aa](https://placehold.co/12x12/5a93aa/5a93aa) `#5a93aa` |
| Cyan       | ![#a1cdd8](https://placehold.co/12x12/a1cdd8/a1cdd8) `#a1cdd8` |
| Magenta    | ![#ad5c7c](https://placehold.co/12x12/ad5c7c/ad5c7c) `#ad5c7c` |
| Orange     | ![#ff8349](https://placehold.co/12x12/ff8349/ff8349) `#ff8349` |
| Yellow     | ![#fda47f](https://placehold.co/12x12/fda47f/fda47f) `#fda47f` |

## Install

```bash
omarchy-theme-install git@github.com:brianstarke/omarchy-terafox-theme.git
```

This installs the theme and applies it immediately. It includes:

- Terminal colors (Alacritty, Kitty, Ghostty)
- Quickshell/OM shell styling
- btop theme (generated from the palette)
- Neovim colorscheme (via nightfox.nvim)
- VS Code: theme (via Nightfox extension)
- Prussian green icon set
- Quickshell lock screen logo
- Nine matching wallpapers

### OpenCode theme (optional)

An [OpenCode](https://opencode.ai/) theme is included under `extras/`. To install it:

```bash
~/.config/omarchy/themes/terafox/install-extras
```

This copies the theme to `~/.config/opencode/themes/` and activates it.

## Lock Screen

A geometric cyberpunk fox logo is displayed on the v4 Quickshell lock screen.

![Lock screen preview](preview-unlock.png)

### Screensaver logo (optional)

An ASCII-art version of the fox logo is included as `screensaver.txt`. To use it as the terminal screensaver:

```bash
cp ~/.config/omarchy/themes/terafox/screensaver.txt \
   ~/.config/omarchy/branding/screensaver.txt
```

### Plymouth boot screen (optional)

To also apply the logo to the Plymouth boot/SDDM login screen:

```bash
omarchy plymouth set-by-theme terafox
```

This requires sudo and rebuilds the initramfs.

## Wallpapers

Nine wallpapers are included that complement the color scheme:

1. **Teal Gradient** — minimalist dark teal abstract gradient
2. **Misty Forest** — dark forest with teal-cyan water
3. **Dark Forest** — foggy forest layers with teal mist
4. **Ireland Forest** — dark mossy floor with deep teal-green shadows
5. **Teal Waves Abstract** — luminous teal ribbons on a dark background
6. **Teal Fog Forest** — dark conifers silhouetted against glowing teal fog
7. **Sunbeams Water** — misty lakeside with teal haze and pale blue water
8. **Evergreen Mist** — atmospheric mountainside conifers in cool fog
9. **Cool Oysters** — oysters on ice with dark moody tones

Cycle through them with `omarchy theme bg next` (or `omarchy-theme-bg-next`).

## Credits

- Colorscheme: [EdenEast/nightfox.nvim](https://github.com/EdenEast/nightfox.nvim)
- Wallpapers sourced from [Wallhaven](https://wallhaven.cc) and [Unsplash](https://unsplash.com) (free licenses)

## License

MIT
