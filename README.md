# Introduction

This is a minimal Vim/[Neovim](https://github.com/neovim/neovim) configuration
in just one file without external dependencies. The purpose is to provide a
light-weight and ready-to-use Vim config for quick editing.

The config is tested in Vim 7.4, Vim 8.0 and Nvim 0.4.0.

<p align="center">
<img src="resources/vim_ui_look.jpg" width="600">
</p>


# How to use

## 🐧 On Unix(mac or linux) systems

### For Neovim/Vim

```bash
mkdir -p ~/.config/nvim && cd ~/.config/nvim
git clone https://github.com/mino29/minimal_vim.git .
cp .vimrc $home/.vimrc
```

## 🪟 On Windows

### For Neovim/Vim

**One line Install**
``` powershell
Invoke-WebRequest https://raw.githubusercontent.com/mino29/minimal_vim/master/utils/install.ps1 -UseBasicParsing | Invoke-Expression
```
