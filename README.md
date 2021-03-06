# π οΈ NeoVim Configuration

## πΊοΈ Table Of Contents

  - [π· Screenshots](#-screenshots)
  - [π Features](#-features)
  - [π§ Installation](#-installation)
  - [π₯οΈ Keybindings](#οΈ-keybindings)
  - [πΊοΈ Structure](#οΈ-structure)

<br/>

<a id="-screenshots"></a>

## π· Screenshots

<div align="left">
<h3 align="left">Dashboard:</h3>
<br/>
  <img src="https://raw.githubusercontent.com/w3samiulazim/Dotfiles/main/.screenshots/nvim-dashboard.png" alt="Nvim Dashboard" width=900px>
<br/>
<br/>
<h3 align="left">Telescope:</h3>
<br/>
  <img src="https://raw.githubusercontent.com/w3samiulazim/Dotfiles/main/.screenshots/nvim-telescope.png" alt="Nvim Telescope" width=900px>
<br/>
<br/>
<h3 align="left">NvimTree:</h3>
<br/>
  <img src="https://raw.githubusercontent.com/w3samiulazim/Dotfiles/main/.screenshots/nvim-telescope.png" alt="Nvim Tree" width=900px>
<br/>
<br/>
<h3 align="left">Floaterm:</h3>
<br/>
  <img src="https://raw.githubusercontent.com/w3samiulazim/Dotfiles/main/.screenshots/nvim-tree.png" alt="Nvim Floaterm" width=900px>
<br/>
<br/>
<h3 align="left">Syntax:</h3>
<br/>
  <img src="https://raw.githubusercontent.com/w3samiulazim/Dotfiles/main/.screenshots/nvim-syntax.png" alt="Nvim Syntax" width=900px>
</div>

<br/>

<a id="-features"></a>

## π Features

- Lovely, informative start screen
- File Navigation with Nvim-Tree.
- Managing tabs with buffer
- Full native LSP support.
- Blazingly fast file search with Telescope π
- Packer - Minimalist Vim Plugin Manager
- Smooth scrolling
- Lazygit inside neovim :ok_hand:
- Distraction-free writing in Vim - GOYO
- Git diff markers
<!-- - Theme switcher `<leader>mm` -->

<br/>

<a id="-installation"></a>

## π§ Installation

1. Install Neovim latest stable version
2. Then install nvim-packer-

   ```bash
   git clone --depth 1 https://github.com/wbthomason/packer.nvim\ ~/.local/share/nvim/site/  pack/packer/start/packer.nvim
   ```

3. Clone this repository

   ```bash
   git clone https://github.com/w3samiulazim/neovim.git
   ```

4. `cd neovim`
5. `chmod +x install.sh`
6. `./install.sh`
7. The install.sh (Post Installation Script) will make a backup named `nvim.bak` if you have an existing config for neovim.

> This might only work on Unix-based systems. You can install this setup on Mac or any Linux distribution.

<br/>

<a id="-keybindings"></a>

## π₯οΈ Keybindings

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

## πΊοΈ Structure

```bash
.
βββ init.lua
βββ install.sh
βββ lua
βΒ Β  βββ blankline.lua
βΒ Β  βββ compe-config.lua
βΒ Β  βββ dashboard.lua
βΒ Β  βββ floaterm.lua
βΒ Β  βββ gitsigns-nvim.lua
βΒ Β  βββ lsp-config.lua
βΒ Β  βββ lsp-install.lua
βΒ Β  βββ mappings.lua
βΒ Β  βββ nvimTree.lua
βΒ Β  βββ plugins.lua
βΒ Β  βββ settings.lua
βΒ Β  βββ statusline.lua
βΒ Β  βββ symbol-outline.lua
βΒ Β  βββ telescope-nvim.lua
βΒ Β  βββ themes
βΒ Β  βΒ Β  βββ material.lua
βΒ Β  βΒ Β  βββ tokyonight.lua
βΒ Β  βΒ Β  βββ tokyodark.lua
βΒ Β  βΒ Β  βββ dracula.lua
βΒ Β  βΒ Β  βββ onedark.lua
βΒ Β  βΒ Β  βββ gruvbox.lua
βΒ Β  βΒ Β  βββ doom-one.lua
βΒ Β  βββ top-bufferline.lua
βΒ Β  βββ treesitter-nvim.lua
βΒ Β  βββ whichkey.lua
βββ README.md

2 directories, 22 files
```

- The init.lua heart of neovim configuration.
- install.sh to install neovim configuration.
- themes directory for themes

> Inspired by [vinodnimbalkar's nvim](https://github.com/vinodnimbalkar/dotfiles/tree/master/.config/nvim).
