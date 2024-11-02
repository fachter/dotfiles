# Dotfiles

This repo contains all my dotfiles, that usually have to be located in my user's home directory.
After cloning the repo perform the following step (from inside the repo folder) to link the files from the repository to your home directory:

```zsh
ln -s "$(realpath .zshrc)" ~/.zshrc && ln -s "$(realpath .ideavimrc)" ~/.ideavimrc
```
