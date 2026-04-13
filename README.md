# Nothingfy

Spicetfy theme inspired by the Nothing® products.

## Screenshots

### NothingBlack
![NothingBlack](screenshots/NothingBlack.png)

### NothingGrey
![NothingGrey](screenshots/NothingGrey.png)

### CMFOrange
![CMFOrange](screenshots/CMFOrange.png)

### CMFDark
![CMFBlack](screenshots/CMFBlack.png)

### CMFGreen
![CMFGreen](screenshots/CMFGreen.png)

### CMFBlue
![CMFBlack](screenshots/CMFBlue.png)

## Configuration

1. Clone this repository into your Spicetify themes folder:

```bash
# Windows
git clone https://github.com/Matteoguerra07/nothingfy "%appdata%\spicetify\Themes\Nothingfy"

# Linux / macOS
git clone https://github.com/Matteoguerra07/nothingfy ~/.config/spicetify/Themes/Nothingfy
```

2. Apply the theme:

```bash
# Windows (PowerShell)
spicetify config current_theme Nothingfy color_scheme CMFDark
spicetify apply

# Linux / macOS
spicetify config current_theme Nothingfy color_scheme CMFDark
spicetify apply
```

> **Note for Linux users:** Make sure Spicetify is installed and in your PATH. If Spotify was installed via Snap or Flatpak, Spicetify may not work correctly — it is recommended to install Spotify via the official `.deb` package or AUR instead.

### Switching color schemes

```bash
spicetify config current_theme Nothingfy color_scheme CMFOrange
spicetify apply
```

## Credits
- Inspired by [Nothing](https://nothing.tech) and [CMF by Nothing](https://nothing.tech/collections/cmf)
- Built with [Spicetify](https://spicetify.app/)
