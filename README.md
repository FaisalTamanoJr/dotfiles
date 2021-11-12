# My Dotfiles (forked from Luke Smith's Voidrice)

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/FaisalTamanoJr/dwm) (window manager)
- [dwmblocks](https://github.com/FaisalTamanoJr/dwmblocks) (statusbar)
- [st](https://github.com/FaisalTamanoJr/st) (terminal emulator)

## Install these dotfiles and all dependencies

Use [my install script](https://github.com/FaisalTamanoJr/install_script) to autoinstall everything:

```
git clone https://github.com/FaisalTamanoJr/install_script.git
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/FaisalTamanoJr/install_script/blob/master/progs.csv).

## Default Desktop Artwork

Gruvbox Lines ([SOURCE](https://store.kde.org/p/1436388/))
