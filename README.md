<div align="center">
  <h1>Bloom</h1>

  [Spicetify](https://github.com/khanhas/spicetify-cli) theme inspired by Microsoft's [Fluent Design System](https://www.microsoft.com/design/fluent).
</div>
<div align="center">
  <h2>Please star and help to shape the future by commenting</h2>
</div>

![dark-1](https://raw.githubusercontent.com/nimsandu/spicetify-bloom/main/bloom_cover.jpg)


<br>


![dark-1](https://raw.githubusercontent.com/nimsandu/spicetify-bloom/main/Dark-1.png)

<br>

## Dependencies

- Latest version of [Spicetify](https://github.com/spicetify/spicetify-cli).
- [Segoe UI](https://en.wikipedia.org/wiki/Segoe#Segoe_UI) font family, comes pre-installed on Windows Vista and newer.
  Segoe UI versions older than 5.37 (older than Windows 8.0) are not officially supported but may work.

## Installation

### Windows (PowerShell)

```powershell
Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/nimsandu/spicetify-bloom/main/install.ps1" | Invoke-Expression
```

### Linux/macOS (Bash)

```bash
curl -fsSL https://raw.githubusercontent.com/nimsandu/spicetify-bloom/main/install.sh | sh
```

...or if you don't want to use the above methods, you can download the installation scripts within the repository.

### Spicetify Marketplace

You may also install the theme from the Spicetify Marketplace.
Simply install [spicetify-marketplace](https://github.com/spicetify/spicetify-marketplace) by following it's
installation instructions. Look for `spicetify-bloom`, and install it.

### Notes
If you're experiencing issues after installing the theme via the Spicetify Marketplace, reset it by going to the Spicetify Marketplace, then scroll all the way down until you see the "Reset Marketplace" button. After that, proceed to install the theme using the PowerShell/Bash methods or by downloading the installation scripts from the repository.

### Important

For the sidebar playlists to show properly, ensure that these two lines are added in the Patch section of your `config-xpui.ini` file:

```ini
[Patch]
xpui.js_find_8008 = ,(\w+=)32,
xpui.js_repl_8008 = ,${1}56,
```

## Customization

apply the theme using these commands

```
spicetify config current_theme Bloom
spicetify config color_scheme dark
spicetify apply
```

### More Options

- You can change the accent color in the theme folder's color.ini file.  
- If you are using Windows, you can hide the window controls by adding the flag `--transparent-window-controls` after Spotify.exe in your Spotify shortcut.  
- Use "Sidebar config" in the Spotify profile menu to hide/unhide and stick/unstick the Liked Songs and My Episodes icons in the sidebar.

## Credits
special thanks and the concept belongs to williamckha
another thanx for @dilith the milkgod
customized the theme by williamckha (https://github.com/williamckha/spicetify-fluent)
Based off [Ziro](https://github.com/schnensch0/ziro) theme by [schnensch](https://github.com/schnensch0)  
[Fluent UI System Icons](https://github.com/microsoft/fluentui-system-icons) by Microsoft Corporation  
[Phosphor Icons](https://github.com/phosphor-icons/phosphor-icons) by Phosphor Icons

## License

[MIT License](LICENSE)
