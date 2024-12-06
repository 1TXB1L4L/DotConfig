# Neovim Configuration

Welcome to my Neovim configuration! This setup is designed to enhance productivity and provide a powerful development environment. Below, you will find an overview of the structure, plugins used, and how to install and contribute to this configuration.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Plugins](#plugins)
  - [Development](#development)
  - [UI Enhancements](#ui-enhancements)
  - [Utility](#utility)
- [Key Mappings](#key-mappings)
- [Contributing](#contributing)

## Overview

This configuration aims to make Neovim a comprehensive and efficient text editor, suitable for coding, navigating files, and managing projects. It leverages the power of Lua to provide a faster and more customizable experience.

## Installation

To use this configuration:

Please make sure you have the following installed:

> Neovim version must be greater than 10

- Node.js
- Python
- FZF
- Ripgrep (optional)
- Lazygit (optional)
- lua-language-server (optional)
- stylua (optional)
- ruff (optional)
- ctags (optional)

1. **Clone the Repository**:\
   `git clone https://github.com/yourusername/nvim-config.git ~/.config/nvim`

1. **Install Neovim** if you haven't already. Make sure you are using Neovim 0.5+.

1. **Run Neovim**:\
   Simply open Neovim, and Lazy will automatically install all the required plugins.

## Directory Structure

```
.
├── init.lua               # Main entry point for Neovim configuration
├── lazy-lock.json         # Lock file for plugin versions
└── lua
    ├── core               # Core configuration files
    ├── plug.lua           # Plugin loader
    └── plugins            # Directory for plugin-specific configurations
        ├── dev            # Development-related plugins
        ├── ui             # UI enhancement plugins
        └── utility        # Utility plugins
```

## Plugins

### Development

- **cmp.lua**: Autocompletion setup.
- **code_runner.lua**: Run code snippets.
- **comment.lua**: Commenting shortcuts.
- **copilot.lua**: AI-assisted coding with GitHub Copilot.
- **db.lua**: Database tools.
- **formatting.lua**: Code formatting tools.
- **illuminate.lua**: Highlight word occurrences.
- **linting.lua**: Linting for error checking.
- **lsp.lua**: Language Server Protocol configurations.
- **python.lua**: Python-specific tools.
- **surround.lua**: Surround text easily.
- **treesitter.lua**: Syntax highlighting.
- **trouble.lua**: Diagnostics management.
- **vc.lua**: Version control integrations.

### UI Enhancements

- **bufferline.lua**: Enhanced buffer line.
- **colorscheme.lua**: Manage color schemes.
- **dressing.lua**: Improved UI elements.
- **file-explorer.lua**: Better file navigation.
- **helpview.lua**: Enhanced help viewer.
- **indent-blankline.lua**: Display indentation levels.
- **lualine.lua**: Status line customization.
- **noice.lua**: Enhanced messaging.
- **notify.lua**: Notification management.
- **nvim-highlight-colors.lua**: Color code highlighting.
- **toggleterm.lua**: Integrated terminal.
- **twilight.lua**: Dim inactive code.
- **vim-maximizer.lua**: Maximize splits.
- **zenmode.lua**: Distraction-free mode.

### Utility

- **auto-pairs.lua**: Auto-closing pairs.
- **hop.lua**: Quick navigation.
- **multicursors.lua**: Multi-cursor editing.
- **oil.lua**: File operations.
- **persistence.lua**: Session management.
- **telescope.lua**: Fuzzy finding.
- **tmux-navigation.lua**: Navigate between tmux and Neovim.
- **url-open.lua**: Open URLs.
- **which-key.lua**: Key binding hints.

## Key Mappings

Key mappings are defined in `keymaps.lua` under the `core` directory. Customize them to suit your workflow.
Every Plugin has its own key mappings in their respective configuration files.

## Contributing

Contributions are welcome! To contribute, fork the repository, create a branch for your feature, and submit a pull request. Make sure to document any new features or changes.

______________________________________________________________________

Enjoy coding with Neovim!
