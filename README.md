
Shell Completion System for the RedHat Brew/Koji Build Systems
==============================================================


Current Status
--------------
Basic version for bash has been implemented.
ZSH version is more comprehensive.


Installation
------------

# ZSH #

Add the directory containing the new completion to your .zshrc fpath e.g.

    fpath=($HOME/zsh-brew-completion $fpath)
    autoload $^fpath/*(N.)

# Bash #

Source the new completion file in your .bashrc e.g.

    source $HOME/bash-brew-completion/brew-koji
