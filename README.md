dotfiles
========

Vim and Bash configs


###Setup

```
mv dotfiles ~/.dotfiles
rm -rf ~/.vim*
mkdir -p ~/.dotfiles/vim
ln -s ~/.dotfiles/vim ~/.vim
ln -s ~/.dotfiles/vim/vimrc ~/.vimrc

mkdir -p ~/.dotfiles/bash
rm ~/.bashrc
ln -s ~/.dotfiles/bash/bashrc ~/.bashrc
rm ~/.bash_profile
ln -s ~/.dotfiles/bash/bash_profile ~/.bash_profile
```
