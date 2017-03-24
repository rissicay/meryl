# Meryl 
#### A vim configuration and backup solution

This is my personal configuration of plugins and mappings for vim. It has been tested on mac and linux. Designed for console use only. Meryl is designed for you to fork! By forking this repository, you'll be to back up any edits that you make, in your github account. Allowing you to easy, transfer your vim configuration between computers and friends.

## Prerequisites

To enable mouse events in mac os x terminal install [mouseterm](https://github.com/brodie/mouseterm).

## Installation

Fork meryl. From your fork, clone a copy of meryl into your home directory. 

    git clone https://github.com/YOURUSERNAME/meryl.git
    
Create a symbolic link for the vim folder in the home directory. Rename the folder to .vim.

    ln -s ~/meryl/vim ~/.vim
    
Create a symbolic link for the .vimrc file.

    ln -s ~/meryl/vim/vimrc ~/.vimrc

Open vim and run

    :PluginInstall

Go to ~/meryl/vim/bundle/command-t and run

    rake make
    
Configure as you like. Enjoy.
