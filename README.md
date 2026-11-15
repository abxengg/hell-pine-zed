# Hell Pine for Zed

A darker, higher-contrast take on Rosé Pine, born inside tmux, for Zed.



## Install

```sh
mkdir -p ~/.config/zed/themes
curl -fsSL https://raw.githubusercontent.com/abxengg/hell-pine-zed/main/themes/hell-pine.json -o ~/.config/zed/themes/hell-pine.json
```

Then pick **Hell Pine** in the theme selector (`cmd-k cmd-t`), or in `settings.json`:

```json
"theme": { "mode": "dark", "dark": "Hell Pine", "light": "One Light" }
```

The repository is also laid out as a Zed extension (`extension.toml` plus `themes/`), so *zed: install dev extension*
on a clone works too.

## Palette

![The Hell Pine palette](https://raw.githubusercontent.com/abxengg/hell-pine.nvim/main/assets/palette.png)

## Other ports

Hell Pine comes from the [VS Code theme](https://github.com/abxengg/hell-pine). Every port is made from the one
palette in [hell-pine.nvim](https://github.com/abxengg/hell-pine.nvim) by its `scripts/extras.py`, so the colours stay the
same everywhere: [Neovim](https://github.com/abxengg/hell-pine.nvim),
[Ghostty](https://github.com/abxengg/hell-pine-ghostty), [WezTerm](https://github.com/abxengg/hell-pine-wezterm), [kitty](https://github.com/abxengg/hell-pine-kitty), [Alacritty](https://github.com/abxengg/hell-pine-alacritty), [tmux](https://github.com/abxengg/hell-pine-tmux), [Starship](https://github.com/abxengg/hell-pine-starship), [btop](https://github.com/abxengg/hell-pine-btop), [fish](https://github.com/abxengg/hell-pine-fish), [fzf](https://github.com/abxengg/hell-pine-fzf).

To change a colour, edit the palette there and run the script; do not edit `themes/hell-pine.json` by hand.

## Licence

MIT, see [LICENSE](LICENSE).
