<h3 align="center">
	<img src="assets/logo.svg" width="100" alt="Logo"/><br/>
	<img src="assets/transparent.svg" height="30" width="0px"/>
	Darkmatter for Alacritty
	<img src="assets/transparent.svg" height="30" width="0px"/>
</h3>

<p align="center">
	<img src="assets/preview.webp" alt="Darkmatter for Alacritty"/>
</p>

An [Alacritty](https://alacritty.org) theme adapted from base16-black-metal-bathory.
Requires Alacritty 0.13 or newer (TOML config).

## Installation

```sh
mkdir -p ~/.config/alacritty/themes
curl -fsSL https://raw.githubusercontent.com/darkmattertheme/alacritty/main/darkmatter.toml \
  -o ~/.config/alacritty/themes/darkmatter.toml
```

## Usage

Import it in `~/.config/alacritty/alacritty.toml`:

```toml
[general]
import = ["~/.config/alacritty/themes/darkmatter.toml"]
```

## Palette

| Slot | Color |
| --- | --- |
| Background | `#121113` |
| Foreground | `#ffffff` |
| Selection | `#222222` |
| Black / bright black | `#121113` / `#333333` |
| Red | `#5f8787` |
| Green | `#fbcb97` |
| Yellow (accent) | `#e78a53` |
| Blue | `#888888` |
| Magenta | `#999999` |
| Cyan | `#aaaaaa` |
| White | `#c1c1c1` |

The core palette lives in [darkmattertheme/darkmatter](https://github.com/darkmattertheme/darkmatter), and every other port is listed at [darkmattertheme.com](https://darkmattertheme.com).

## Credits

Adapted from [base16-black-metal-bathory](https://github.com/metalelf0/base16-black-metal-scheme).
