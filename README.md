# README

Just started creating env linux env.

## TODO:
- add automation on installs
- setup Nodejs 🤮 for sveltekit ❤️
- setup golang
- setup rust
- setup I3 maybe?


## zsh ( oh my zsh )
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
## tmux
```bash
sudo apt install tmux
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
### Installing plugins

1. Add new plugin to `~/.tmux.conf` with `set -g @plugin '...'`
2. Press `prefix` + <kbd>I</kbd> (capital i, as in **I**nstall) to fetch the plugin.

You're good to go! The plugin was cloned to `~/.tmux/plugins/` dir and sourced.

### Uninstalling plugins

1. Remove (or comment out) plugin from the list.
2. Press `prefix` + <kbd>alt</kbd> + <kbd>u</kbd> (lowercase u as in **u**ninstall) to remove the plugin.

All the plugins are installed to `~/.tmux/plugins/` so alternatively you can
find plugin directory there and remove it.

## neovim
```bash
sudo add-apt-repository ppa:neovim-ppa/unstable -y
sudo apt update
sudo apt install make gcc ripgrep unzip git xclip neovim
```
## Github CLI ( because im lazy )
```
sudo apt install gh
```

## Dbeaver
Db viewer for sqlite
[Dbeaver download](https://dbeaver.io/download/2/)

## Dotnet sdk 8.0

For nyere installasjon: [Setup guides](https://dotnet.microsoft.com/en-us/download)

```bash
sudo apt-get update && \
  sudo apt-get install -y dotnet-sdk-8.0
```

## Nodejs

## Settings

Disable touchpad tap and drag (UI):
```bash 
sudo apt install dconf-editor
dconf-editor

# Find org/gnome/desktop/peripherals/touchpad
```

Disable touchpad tap and drag (term only):
```bash
gsettings set org.gnome.desktop.peripherals.touchpad tap-and-drag false

# check
gsettings get org.gnome.desktop.peripherals.touchpad tap-and-drag
```
