dotfiles
========

Required dotfiles for environment setup

Includes:

  * Vim Config
  * Git Config

Quick Install
-------------

```
cd ~/ && \
git clone git@github.com:thestonefox/dotfiles.git && \
ln -s dotfiles/.vim/ ~/.vim && \
ln -s dotfiles/.vimrc ~/.vimrc && \
ln -s dotfiles/.gitconfig ~/.gitconfig && \
ln -s dotfiles/.gitignore ~/.gitignore && \
./dotfiles/shortcuts.sh && \
source ~/.bashrc
```

Installing
----------

* cd user home directory `cd ~/`
* Git clone repo `git clone git@github.com:thestonefox/dotfiles.git`
* Symlink .vim `ln -s dotfiles/.vim/ ~/.vim`
* Symlink .vimrc `ln -s dotfiles/.vimrc ~/.vimrc`
* Symlink .gitconfig `ln -s dotfiles/.gitconfig ~/.gitconfig`
* Symlink .gitignore `ln -s dotfiles/.gitignore ~/.gitignore`
* Run shortcuts.sh to get command shortcuts `./shortcuts.sh`

Command Shortcuts
-----------------

The following alias shortcuts can be added by running `./shortcuts.sh`

* gitl1 -n = shortcut for `git log --oneline -n` [usage: gitl1 -5]
* gits = shortcut for git status
* gitb = shortcut for git branch
