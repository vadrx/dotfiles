# dotfiles
My dotfiles - oh-my-zsh, neovim config

Terminal
---
First Install ZSH:
### Ubuntu:
```bash
sudo apt-get install zsh
```
### Mac:
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install zsh
```
Now install [Oh-My-ZSH](https://github.com/robbyrussell/oh-my-zsh).

NeoVim
---
### Install [NeoVim](https://github.com/neovim/neovim/wiki/Installing-Neovim) 
and run this commands:
 ```bash
mkdir .config
mkdir .config/nvim
```
### Install [Vimmic](https://github.com/CharlesGueunet/vimmic/) 
and run this commands:
```bash
git clone https://github.com/CharlesGueunet/vimmic.git ".vimmic"
ln -rsf .vimmic/.vimrc .config/nvim/init.vim
```

My modifications
---

### NeoVim:
* Install [deoplete](https://github.com/Shougo/deoplete.nvim);
* Install [deoplete-clang](https://github.com/zchee/deoplete-clang).
