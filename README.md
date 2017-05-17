
<p align="center"><img width="620px" src="http://i.imgur.com/77xXWrA.jpg"/></p>
<p align="center"><img width="450px" src="http://i.imgur.com/JXb5aRO.jpg"></p>

[![GitHub tag](https://img.shields.io/github/release/equinusocio/vsc-material-theme.svg?style=flat-square)](https://github.com/equinusocio/vsc-material-theme/releases)   [![GitHub tag](https://img.shields.io/github/issues/equinusocio/vsc-material-theme.svg?style=flat-square)](https://github.com/equinusocio/vsc-material-theme/issues)
<a href="https://code.visualstudio.com/updates/v1_12"><img src="https://img.shields.io/badge/VS_Code-v1.12+-373277.svg?style=flat-square"/></a> <a href="https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme"><img src="http://vsmarketplacebadge.apphb.com/installs/Equinusocio.vsc-material-theme.svg?style=flat-square"/></a> <a href="https://marketplace.visualstudio.com/items/Equinusocio.vsc-material-theme"><img src="http://vsmarketplacebadge.apphb.com/rating-short/Equinusocio.vsc-material-theme.svg?style=flat-square"/></a> [![Beerpay](https://beerpay.io/equinusocio/vsc-material-theme/badge.svg?style=beer)](https://beerpay.io/equinusocio/vsc-material-theme)


The most epic theme meet Visual Studio Code. Please note that this theme is still in Beta (β) release. You can help by reporting issues [here](https://github.com/equinusocio/vsc-material-theme/issues)

# Getting started
You can install this awesome theme through the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme).

## Installation

Launch *Quick Open*
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:
```shell
ext install vsc-material-theme
```

#### Packaged VSIX Extension

[Download the latest .vsix release](https://github.com/equinusocio/vsc-material-theme/releases/latest)  file from the GitHub repository and install it from the command line
```shell
code --install-extension vsc-material-theme-*.*.*.vsix
```
or from within VS Code by launching *Quick Open* and running the *Install from VSIX...* command.

##### GitHub Repository Clone

Change to your `.vscode/extensions` [VS Code extensions directory](https://code.visualstudio.com/docs/extensions/install-extension#_side-loading).
Depending on your platform it is located in the following folders:
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> **Linux** `~/.vscode/extensions`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> **macOs** `~/.vscode/extensions`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> **Windows** `%USERPROFILE%\.vscode\extensions`

Clone the Material Theme repository as `Equinusocio.vsc-material-theme`:
```shell
git clone https://github.com/equinusocio/vsc-material-theme.git Equinusocio.vsc-material-theme
```


## Activate theme

Launch *Quick Open*,
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `Shift+⌘+P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

run the `Preferences: Color Theme` command and select one of the `Material Theme` themes from the drop-down menu.

The color theme drop-down can alternatively be opened via *File* (*Code* on macOS) > *Preferences* > *Color Theme*.


## Activate File Icons

Launch *Quick Open*,
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `Shift+⌘+P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

run the `icon theme` command and select `Material Theme Icons` from the drop-down menu.

# Recommended settings for a better experience:

```json
    // Controls the font family.
    "editor.fontFamily": "Operator Mono",
    // Controls the line height. Use 0 to compute the lineHeight from the fontSize.
    "editor.lineHeight": 24,
    // Enables font ligatures
    "editor.fontLigatures": true,
```

# Other resources
- **AppIcon:** [Download](https://github.com/equinusocio/vsc-material-theme/files/989048/vsc-material-theme-appicon.zip) the official Material Theme app icon for Visual Studio code

# Acknowledgements
- [@balanceiskey](https://github.com/balanceiskey) for the theme builder.


<p align="center"> <img src="https://equinusocio.gallerycdn.vsassets.io/extensions/equinusocio/vsc-material-theme/0.0.14/1494970083238/Microsoft.VisualStudio.Services.Icons.Default" width=16 height=16/> Copyright &copy; 2017 Mattia Astorino</p>

<p align="center"><a href="http://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/License-Apache_2.0-5E81AC.svg?style=flat-square"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-5E81AC.svg?style=flat-square"/></a></p>
