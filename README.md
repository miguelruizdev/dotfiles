# **.DOTFILES**

Repo for storing local configuration of common dev tools.

Easy colonizing of new machines by externalizing config file location.

To install clone this repo to your home directory like so:

	git clone https://github.com/miguelruizdev/dotfiles.git ~/.dotfiles

To symlink with actual files under home directory when migrating across systems:
	
	ln -s ~/.dotfiles/vim/vimrc.symlink ~/.vimrc
	ln -s ~/.dotfiles/vim/vim ~/.vim

Tools covered:
- vim

To be covered:
- zsh
- iterm2

Based on: https://github.com/mscoutermarsh/dotfiles
