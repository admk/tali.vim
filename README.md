# tali.vim

Neovim / Vim syntax highlighting for [tali][tali].

## Screenshot

[![screenshot][screenshot]][screenshot]

## Installation

- [**lazy.nvim**][lazy.nvim] (for Neovim):
  ```lua
  {
    "admk/tali.nvim",
    ft = "tali",
  },
  ```

- [**vim-plug**][vim-plug] (for Vim):
  ```vim
  call plug#begin('~/.vim/plugged')
    Plug 'admk/tali.nvim', { 'ft': 'tali' }
  call plug#end()
  ```

[tali]: https://github.com/admk/tali
[screenshot]: https://raw.githubusercontent.com/admk/tali.vim/refs/heads/main/assets/example.png
[lazy.nvim]: https://github.com/folke/lazy.nvim
[vim-plug]: https://github.com/junegunn/vim-plug
