This repo stores my personal tmux config and related files.

## Installation

_Recursively_ clone this repo into something like `~/dotfiles/dottmux`,
then in your home directory add symlinks to this repo's `.tmux` and
`.tmux.conf`.  For example:

```bash
mkdir -p ~/dotfiles
cd ~/dotfiles
git clone --recurse-submodules git@github.com:fardaniqbal/dottmux.git
ln -si dotfiles/dottmux/.tmux ~/.tmux
ln -si dotfiles/dottmux/.tmux.conf ~/.tmux.conf
```
