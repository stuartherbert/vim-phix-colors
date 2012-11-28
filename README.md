# Phix Color Scheme for Vim

This is a port of my [Phix Color Scheme for Sublime Text 2](https://github.com/stuartherbert/sublime-phix-color-scheme). It supports both console terminals and GUI.

It isn't a 100% perfect port, due to the differences in syntax highlighting between Sublime Text 2 and Vim, but it's close enough.

## Example Screenshots

Inside vim from the console:

![Phix Color Scheme inside vim w/ xterm-256](https://github.com/stuartherbert/vim-phix-colors/blob/master/examples/vim-xterm-256.png)

and inside GVim on Ubuntu 12.10:

![Phix Color Scheme inside GVim](https://github.com/stuartherbert/vim-phix-colors/blob/master/examples/vim-gvim.png)

## How To Install

If you already use [Pathogen](https://github.com/tpope/vim-pathogen/), simply add this colour scheme to your _bundles_ folder:

    cd .vim/bundles
    git submodule add git@github.com:stuartherbert/vim-phix-colors.git

Or, [download the phix.vim file](https://raw.github.com/stuartherbert/vim-phix-colors/master/colors/phix.vim), save it as _~/.vim/colors/phix.vim_.

Finally, in your .vimrc file, add the line

    colorscheme phix

to tell Vim to load the Phix colour scheme when it starts up.

## Pull Requests Welcome

Right now, this colour scheme works best with PHP files, as that's the programming language I spend most of my time working with.  Pull requests for other languages are most welcome!