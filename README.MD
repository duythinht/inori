## The Inori colors scheme for vim

This colorscheme based on 256colors-terminal, working perfectly on gnome-terminal, iterm, tmux, screen-256colors, MacVim, gvim...

**You don't need to import terminal's colors pallete**

Help me improve it (please take a screen shot for bug or something you want change): https://github.com/duythinht/inori/issues

If you use terminal, setup with xterm-256color or something like that

	# example for using gnome-terminal
	export TERM=xterm-256color

For better experience, you should set terminal background to #262626 and text color to #c0c0c0

## Install using Pathogen:

	cd ~/.vim/bundle
	git clone https://github.com/duythinht/inori

## Install using Vundle

	Plugin 'duythinht/inori'

## Modify .vimrc

	syntax enable
	silent! colorscheme inori

Previews:

![Vim Inori](https://raw.githubusercontent.com/duythinht/inori/master/image/preview.png)
