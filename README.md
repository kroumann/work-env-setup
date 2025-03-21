# work environment setup

This is Ansible configuration script for Debian like machine configuration. it configures a work environment with some package install and configuration.  It should also work on many other \*nix variants with minor changes. It
performs the following tasks:


- Install and configure Zsh:
  - make sure it exists,
  - set it as the default shell for the user specified by the role.
- Install Oh My Zsh with [powerlevel10k](https://github.com/romkatv/powerlevel10k) theme.
  - Install Meslo from (nerd-fonts) package 
  - Configure (Oh My) Zsh by adding custom path and plugins.
  - Install custom powerlevel10k config
- Install tmux and [oh-my-tmux](https://github.com/gpakosz/.tmux) dotfiles
- Install neovim and treesitter
