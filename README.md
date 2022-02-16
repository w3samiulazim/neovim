# 🛠️ NeoVim Configuration

## 🗺️ Table Of Contents

<<<<<<< HEAD
  - [📷 Screenshots](#️-screenshots)
  - [🎁 Features](#️-features)
  - [🔧 Installation](#️-installation)
=======
- [🛠️ NeoVim Configuration](#️-neovim-configuration)
  - [🗺️ Table Of Contents](#️-table-of-contents)
  - [📷 Screenshots](#-screenshots)
  - [🎁 Features](#-features)
  - [🔧 Installation](#-installation)
>>>>>>> parent of 56c116c (Update README.md)
  - [🖥️ Keybindings](#️-keybindings)
  - [🗺️ Structure](#️-structure)

<br/>

<a id="-screenshots"></a>

## 📷 Screenshots

<div align="left">
<h3 align="left">Dashboard:</h3>
<br/>
  <img src="https://raw.githubusercontent.com/iamsamiulazim/Dotfiles/main/.screenshots/nvim-dashboard.png" alt="Nvim Dashboard" width=900px>
<br/>
<br/>
<h3 align="left">Telescope:</h3>
<br/>
  <img src="https://raw.githubusercontent.com/iamsamiulazim/Dotfiles/main/.screenshots/nvim-telescope.png" alt="Nvim Telescope" width=900px>
<br/>
<br/>
<h3 align="left">NvimTree:</h3>
<br/>
  <img src="https://raw.githubusercontent.com/iamsamiulazim/Dotfiles/main/.screenshots/nvim-telescope.png" alt="Nvim Tree" width=900px>
<br/>
<br/>
<h3 align="left">Floaterm:</h3>
<br/>
  <img src="https://raw.githubusercontent.com/iamsamiulazim/Dotfiles/main/.screenshots/nvim-tree.png" alt="Nvim Floaterm" width=900px>
<br/>
<br/>
<h3 align="left">Syntax:</h3>
<br/>
  <img src="https://raw.githubusercontent.com/iamsamiulazim/Dotfiles/main/.screenshots/nvim-syntax.png" alt="Nvim Syntax" width=900px>
</div>

<br/>

<a id="-features"></a>

## 🎁 Features

- Lovely, informative start screen
- File Navigation with Nvim-Tree.
- Managing tabs with buffer
- Full native LSP support.
- Blazingly fast file search with Telescope 😎
- Packer - Minimalist Vim Plugin Manager
- Smooth scrolling
- Lazygit inside neovim :ok_hand:
- Distraction-free writing in Vim - GOYO
- Git diff markers
<!-- - Theme switcher `<leader>mm` -->

<br/>

<a id="-installation"></a>

## 🔧 Installation

1. Install Neovim latest stable version
2. Then install nvim-packer-

   ```bash
   git clone --depth 1 https://github.com/wbthomason/packer.nvim\ ~/.local/share/nvim/site/  pack/packer/start/packer.nvim
   ```

3. Clone this repository

   ```bash
   git clone https://gitlab.com/samiulazim/neovim.git
   ```

4. `cd neovim`
5. `chmod +x install.sh`
6. `./install.sh`
7. The install.sh (Post Installation Script) will make a backup named `nvim.bak` if you have an existing config for neovim.

> This might only work on Unix-based systems. You can install this setup on Mac or any Linux distribution.

<br/>

<a id="-keybindings"></a>

## 🖥️ Keybindings

The table showing some extra key mappings:

| Functions               | Keybinds                   |
| ----------------------- | -------------------------- |
| Leader Key              | `Space`                    |
| NvimTree                | `Ctrl + n`                 |
| Tabbing through buffers | `Ctrl + Left, Right Arrow` |
| Floaterm                | `Space + t + t`            |
| Ranger                  | `Space + t + r`            |
| Vifm                    | `Space + t + v`            |
| Git                     | `Space + t + g`            |
| Node                    | `Space + t + n`            |
| Python                  | `Space + t + p`            |
| Fzf                     | `Space + t + f`            |
| Telescope               | `Space + f + f`            |

You need to install: Ranger or Vifm, Lazygit, Fzf, Nodejs, Python, on your system.

<br/>

<a id="-structure"></a>

## 🗺️ Structure

```bash
.
├── init.lua
├── install.sh
├── lua
│   ├── blankline.lua
│   ├── compe-config.lua
│   ├── dashboard.lua
│   ├── floaterm.lua
│   ├── gitsigns-nvim.lua
│   ├── lsp-config.lua
│   ├── lsp-install.lua
│   ├── mappings.lua
│   ├── nvimTree.lua
│   ├── plugins.lua
│   ├── settings.lua
│   ├── statusline.lua
│   ├── symbol-outline.lua
│   ├── telescope-nvim.lua
│   ├── themes
│   │   ├── material.lua
│   │   └── tokyonight.lua
│   │   └── tokyodark.lua
│   │   └── dracula.lua
│   │   └── onedark.lua
│   │   └── gruvbox.lua
│   │   └── doom-one.lua
│   ├── top-bufferline.lua
│   ├── treesitter-nvim.lua
│   └── whichkey.lua
└── README.md

2 directories, 22 files
```

- The init.lua heart of neovim configuration.
- install.sh to install neovim configuration.
- themes directory for themes

> Inspired by [vinodnimbalkar's nvim](https://github.com/vinodnimbalkar/dotfiles/tree/master/.config/nvim).
