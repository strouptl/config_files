# Config Files

Dev Environment config files for Tmux, Vim, Git, and Ghostty.

## Details
Tmux
- Use Vim keybindings for panel navigation, text selection, and copy/pasting
- Reduce status bar brightness (dark green)

Vim
- Display line numbers
- Disable wrapping
- Use 2 spaces for tab
- Set dark background
- See config\_files/vimrc for other

Git
- Use vim for commit messages
- Exclude vim temporary files in git repos
- Sort version tags by refname from latest to oldest
- Use "master" branch as default (instead of main)

## Instructions

1. Clone this repository to your computer

```sh
git clone https://github.com/strouptl/config_files.git
```

2. Run the install script

```sh
./config_files/bin/install
```

## Vim Exercises

```sh
vim config_files/resources/vim_exercises.txt
```

## Other resources
- [Ghostty configuration](https://raw.githubusercontent.com/strouptl/config_files/refs/heads/master/resources/Ghostty%20Config.txt)
- [Ctrlp](https://ctrlpvim.github.io/ctrlp.vim/) (a fuzzy search plugin for Vim)
- [Vim exercises](https://raw.githubusercontent.com/strouptl/config_files/refs/heads/master/resources/vim_exercises.txt)
