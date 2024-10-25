# Neovim Configuration

This repository contains my Neovim configuration files with a modular setup, utilizing various plugins to enhance development productivity and user experience.

## File Structure

The configuration is organized into the following structure:

```plaintext
~/.config/nvim
├── lua
│   ├── config
│   │   └── lazy.lua             # Lazy load plugin configuration
│   └── plugins
│       ├── alpha.lua            # Dashboard for Neovim
│       ├── catppuccin.lua       # Theme configuration (Catppuccin)
│       ├── completions.lua      # Autocompletion setup
│       ├── git-stuff.lua        # Basic Git configurations
│       ├── gitsigns.lua         # Git signs for file changes
│       ├── lsp-config.lua       # Language server protocol configuration
│       ├── neo-tree.lua         # File explorer configuration
│       ├── none-ls.lua          # Null-ls for LSP diagnostics and formatting
│       ├── nvim-tmux-navigation.lua # Seamless navigation between Neovim and tmux
│       ├── oil.lua              # Enhance handling of buffer and file operations
│       ├── swagger-preview.lua  # Swagger preview plugin for API documentation
│       ├── telescope.lua        # Fuzzy finder and file search
│       ├── treesitter.lua       # Treesitter for syntax highlighting and more
│       └── vim-test.lua         # Testing framework integration
└── init.lua                     # Main Neovim configuration file

