# <p align="center">Neovim</p>
<div align="center">
  <p>Neovim is a  hyperextensible, open-source, feature-rich, modern, next-gen fork of</p>
  <p><a href="https://github.com/vim/vim">Vim</a> - one of the oldest, but still popular text editors</p>
</div>

## Features
* **Write config files using lua**: Ability to write config files, extensions, themes, and plugins in [Lua](https://www.lua.org/) instead of using the outdated *Vimscript*. 
* **Remote API**: Neovim's remote API allows external applications to interact with the editor, enabling features like language servers and debug adapters.
* **Codebase cleanup**: Neovim removed outdated and redundant code, making the codebase more manageable and easier to contribute to.
* **Improved testing infrastructure**: Neovim introduced a more comprehensive testing framework, ensuring that changes are thoroughly tested and validated.
* **Asynchronous I/O**: Neovim uses asynchronous I/O to handle tasks in the background, reducing latency and making the editor feel more responsive.
* **Mouse Support**: Ability to use the mouse for navigation.

## System requirements
* Any 64-bit processor.
* 512 MB of RAM is the minimum, but recommended is at least 2 GB.

## Installation
### [Debian](https://www.debian.org/) based distributions 
```
apt install neovim
```

### [Arch](https://archlinux.org/) based distributions:
```
pacman -S neovim
yay -S neovim # Or if you use yay 
```

### [Fedora](https://fedoraproject.org/)
```
sudo dnf install -y neovim python3-neovim
```

### [Flatpak](https://www.flatpak.org/)
```
flatpak install flathub io.neovim.nvim
flatpak run io.neovim.nvim
```
### [Gentoo](https://www.gentoo.org/)
```
emerge -a app-editors/neovim
```
### [Chocolatey](https://chocolatey.org/)
```
choco install neovim
```
### [Scoop](https://scoop.sh/)
```
scoop bucket add main
scoop install neovim
```
### macOS / OS X
For x86_64:
```
curl -LO https://github.com/neovim/neovim/releases/download/nightly/nvim-macos-x86_64.tar.gz
tar xzf nvim-macos-x86_64.tar.gz
./nvim-macos-x86_64/bin/nvim
```

For arm64:
```
curl -LO https://github.com/neovim/neovim/releases/download/nightly/nvim-macos-arm64.tar.gz
tar xzf nvim-macos-arm64.tar.gz
./nvim-macos-arm64/bin/nvim
```

### [Homebrew](https://brew.sh/) on macOS or **Linux**
```
brew install neovim
```

### Your Distro/Package manager isn't here? 
Checkout the [official installation documentation](https://github.com/neovim/neovim/blob/master/INSTALL.md).

### Build from source
For building from source checkout the [official building documentation](https://github.com/neovim/neovim/blob/master/BUILD.md)

## Usage
Get started by typing `nvim` in your terminal. Neovim has a steep learning curve, user guide is available under the `:help` command.  

## Known issues and troubleshooting
See the `:help faq` command.  

Michał Libera
