# dotfiles

This is my dotfile repository, which includes configuration for my oft-used command-line tools. Chief amongst them are zsh (my shell), vim (my text editor), and tmux.

## Additional Dependencies
In addition to vim, zsh, and tmux, you'll want to install a few other projects. An install script for these is to come:

### oh-my-zsh
All of the hard work for zsh. [Get it here](https://github.com/robbyrussell/oh-my-zsh).

### reattach-to-user-namespace
This makes copy-and-paste work in tmux for OS/X. To get it:

    brew install reattach-to-user-namespace

Then, just use <tmux-prefix> y to paste from the OS/X clipboard.
