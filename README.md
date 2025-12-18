# HyperTheme for FOSSBilling

## Overview

HyperTheme is a modern, high-performance client area theme for FOSSBilling. It is a fork of the [Tide theme](https://github.com/getpinga/tide) by [@getpinga](https://github.com/getpinga). HyperTheme enhances the core aesthetic with a streamlined navigation, refined dashboard, and full dark mode support.

## Installation

Follow these steps to install the HyperTheme:

1. Clone this repository or download the latest version.
2. Extract the files and move the `HyperTheme` directory into the `FOSSBilling directory/themes`.
3. Change the directory owner to the user your web server runs under. For example: `chown -Rf www-data:www-data HyperTheme/`.
4. Set permissions to `750` using chmod: `chmod -Rf 750 HyperTheme/`.
5. Navigate to `Settings -> Themes` in the FOSSBilling admin panel and select `HyperTheme` as the default theme.

## Upgrade

To upgrade to a newer version of HyperTheme:

1. Clone this repository or download the latest version.
2. Backup your `FOSSBilling directory/themes/HyperTheme/config/settings_data.json` and any custom assets.
3. Extract the latest version and move the `HyperTheme` directory into `FOSSBilling directory/themes`, overwriting all files.
4. Restore your `settings_data.json` and any custom assets from the backup.
5. Change the directory owner and permissions as specified in the installation steps.

## Theme Customization

HyperTheme allows you to customize colors and layout via theme settings and CSS. To make manual CSS changes, edit the `assets/css/hyper-ui.css` file.

## Credits

- Original theme: [Tide](https://github.com/getpinga/tide) by [@getpinga](https://github.com/getpinga)
- Modified and maintained by: [rownok860](https://github.com/rownok860)
