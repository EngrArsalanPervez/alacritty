# alacritty
alacritty.toml

# Themes

```bash
# https://github.com/alacritty/alacritty-theme

# We use Alacritty's default Linux config directory as our storage location here.
mkdir -p ~/.config/alacritty/themes
git clone https://github.com/alacritty/alacritty-theme ~/.config/alacritty/themes
```

# alacritty.toml

```bash
# nvim ~/.config/alacritty/alacritty.toml

[general]
import = [
    # "~/.config/alacritty/themes/themes/{theme}.toml"
    # "~/.config/alacritty/themes/themes/ubuntu.toml"
    "~/.config/alacritty/themes/themes/falcon.toml"
]

[window]
startup_mode = "Maximized"

[font]
normal = { family = "ComicShannsMono Nerd Font", style = "Regular" }
size = 13.0

# Fine-tune spacing (adjust if text looks too loose/tight)
[font.offset]
x = 0
y = 0

[font.glyph_offset]
x = 0
y = 0

[[keyboard.bindings]]
key = "F11"
action = "ToggleFullscreen"

```
