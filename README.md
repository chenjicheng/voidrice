fork https://github.com/LukeSmithxyz/voidrice

# The Voidrice ([Chen Jicheng](https://www.chenjicheng.com/)'s dotfiles)

These are the dotfiles deployed by [CARBS](https://carbs.run/) and as seen on

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- bash (shell)
	- dolphin (file manager)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.bash_profile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/chenjicheng/dwm) (window manager)
- [dwmblocks](https://github.com/chenjicheng/dwmblocks) (dwmblocks)
- [st](https://github.com/chenjicheng/st) (terminal emulator)

I also recommend trying out
[mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard), which additionally
works with this setup. It gives you an easy-to-install terminal-based email
client regardless of your email provider. It is integrated into these dotfiles
as well.

## Install these dotfiles and all dependencies

Use [CARBS](https://carbs.run/) to autoinstall everything:

```
curl -LO carbs.run/carbs.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/chenjicheng/CARBS/blob/main/progs.csv).

## Default Desktop Artwork

[Wolfgang Hasselmann](https://unsplash.com/photos/CsQD3CyTR0M)'s [**Photo**](https://unsplash.com/photos/CsQD3CyTR0M)
