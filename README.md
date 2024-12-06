# dotFiles

This is the dotfiles repository for my personal configuration files. It contains my configuration for my programming setup on my mobile.

**Estimate Size after setup: 1.5GB - 2.0GB**

## Table of Contents

- [Installation](#installation)
- [Neovim](#neovim)
- [Zsh](#zsh)
- [Bash](#bash)
- [Termux](#termux)
- [Code-Server](#code-server)
- [Fzf-git](#fzf-git)
- [Shell](#shell)
- [Contributing](#contributing)

## Installation

```bash
git clone https://github.com/abrarishere/dotFiles
```

This will download the repository to your local machine.

## Neovim

The neovim configuration files are stored in the [.config/nvim](.config/nvim) directory. It contains the configuration for the neovim editor that is more than just a text editor.

Further Details can be found in the [README.md](NEOVIM.md) file.

## Zsh

- [.zshrc-zap](.zshrc-zap)
  This is the zsh configuration file for the ZAP plugin. It is a zsh plugin that provides a minimal zsh setup.

### Installation

```bash
cp .zshrc-zap ~/.zshrc
```

## Bash

The bash configuration file is stored in the [bash.bashrc](bash.bashrc) directory. It contains the configuration for the bash shell.

### Installation

```bash
cp bash.bashrc /etc/bash.bashrc
```

> Note: The bash configuration file is for the root user. You can change it according to your need.This is for the termux shell if ypu are using any other distro may be you have to rename it to `.bashrc`.

## Termux

The termux configuration files are stored in the [.termux](.termux) directory. It contains the configuration for the termux shell, background, and font.

### Installation

```bash
cp -r .termux ~/
```

## Code-Server

The code-server configuration file is stored in the [code-server](code-server) directory. It contains the configuration for the code-server.They can be used in vscode or code-server/code-oss.

### Installation

```bash
cp -r code-server ~/.config/
```

## Fzf-git

The fzf-git configuration file is stored in the [fzf-git.sh](fzf-git.sh) directory. It contains the configuration for the fzf-git. It is a shell script that provides a fuzzy finder for git commands.

> Note: The fzf-git script is not mine. It is a fork of the original fzf-git script. The original script can be found [here](https://github.com/junegunn/fzf-git.sh).

### Installation

```bash
cp -r fzf-git.sh ~/
```

## Shell

These are the shell scripts that I you use to download some of the tools that I use in my setup.

### Installation

```bash
cp -r sh ~/
cd sh
chmod +x full.sh
chmod +x install-sdk.sh
```

> Note: The shell scripts have all configurations for mine setup. It also set git with my name and email. You can change it according to your need.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
