# My dotfiles for WSL
Repo to organize my dotfiles for WSL

## Install
```
git clone --recurse-submodules --bare git@github.com:Ricebal/wsl-dotfiles.git ~/.dotfiles
git --git-dir=$HOME/.dotfiles --work-tree=$HOME checkout master
git --git-dir=$HOME/.dotfiles --work-tree=$HOME pull origin master
git --git-dir=$HOME/.dotfiles --work-tree=$HOME config --local status.showUntrackedFiles no
config submodule update --init --recursive
```
