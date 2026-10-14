<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/mierak/rmpc">rmpc</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/rmpc/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/rmpc?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/rmpc/issues"><img src="https://img.shields.io/github/issues/catppuccin/rmpc?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/rmpc/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/rmpc?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Usage

Themes are named `catppuccin-<flavor>-<accent>`, with flavors `latte`, `frappe`, `macchiato`, `mocha` and the 14 Catppuccin accents (`rosewater`, `flamingo`, `pink`, `mauve`, `red`, `maroon`, `peach`, `yellow`, `green`, `teal`, `sky`, `sapphire`, `blue`, `lavender`).

1. Copy the theme of your choice from [`themes/`](./themes) to `~/.config/rmpc/themes/`.
2. Set it in your `config.ron`, without the extension:

   ```ron
   theme: Some("catppuccin-mocha-mauve"),
   ```

To try a theme without touching the config, point rmpc at the file directly:

```sh
rmpc --theme themes/mocha/catppuccin-mocha-mauve.ron
```

The themes only change colors. Layout, symbols and components are the same as rmpc's default theme, so they combine with any `config.ron`.

## Development

The themes are generated from [`rmpc.tera`](./rmpc.tera) with [Whiskers](https://github.com/catppuccin/whiskers). Edit the template, then run:

```sh
just build
```

## 💝 Thanks to

- [8098](https://github.com/KokaKiwi)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
