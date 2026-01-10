# Node Visual Manager

Node Visual Manager is a VSCode extension that shows the NVM functionalities directly in the VSCode editor without having to open a terminal, it is only necessary to choose the version in a simple and ergonomic interface.

Note: The extension does not automatically install NVM; it works as a wrapper around an existing installation.

## Requirements

It is necessary to have version 1.2.2 installed in the case of Windows.

<https://github.com/coreybutler/nvm-windows/releases>

It is necessary to have NVM SH installed in the case of Linux.

<https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating>

## Features

![Preview](/resources/preview.gif)

![Preview](/resources/linux_preview.gif)

NVM has the following functionalities.

- ### Install versions (Current, LTS, Old versions)

- ### Uninstall versions of node

- ### Switch between versions

- ### Enable NVM (Just for Windows)

- ### Disable NVM (Just for Windows)

## Known Issues

Functionality not verified on macOS.

Simultaneous use of multiple Node versions across different workspaces is not supported.

## Release Notes

### 1.2.0

Bug fixes.

Added support for automatic reading of .nvmrc files.

Removed automatic installation of NVM tool versions.

Updated Linux-specific Node version handling.

---

## Issues Repository

<https://github.com/Kanin-020/Node-Visual-Manager-Issues>
