# Ditana Config VSCode

This Arch Linux package provides a preconfigured setup of Visual Studio Code for Ditana GNU/Linux, optimizing it for an enhanced coding experience.

## Description

Ditana Config VSCode installs and configures the open source build of Visual Studio Code, a highly adaptable source code editor.
It includes the dependency [code-marketplace](https://aur.archlinux.org/packages/code-marketplace) that enables the marketplace for the open source build.
In addition, it sets up font ligatures for improved readability.

## Features

- Preconfigured Visual Studio Code optimized for Ditana GNU/Linux
- Includes the marketplace for full functionality
- Enables font ligatures by default
- Configures font sizes for editor and integrated terminal

## Configuration

The Visual Studio Code editor is configured with the following settings:

- Font ligatures enabled
- Editor font size set to 12
- Integrated terminal font size set to 12

These settings are optimized for use with the default Ditana XFCE monospace font (JetBrains Mono Nerd), which supports ligatures.

## Installation

This Arch package is available in The Ditana GNU/Linux repopsitory. During installation it is an optional development package.

## Usage

After installation, you can launch Visual Studio Code from your application menu or by running `code` in the terminal.
The preconfigured settings will be automatically applied.

## Customization

You can further customize your Visual Studio Code settings by editing the `settings.json` file located at `~/.config/Code - OSS/User/settings.json`.

## Support

For issues, feature requests, or contributions related to the Ditana configuration of Visual Studio Code, please use the GitHub issue tracker or submit a pull request.

For Visual Studio Code-specific questions, refer to the [official Visual Studio Code documentation](https://code.visualstudio.com/docs).
