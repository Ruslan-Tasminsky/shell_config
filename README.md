# shell_config

</br>

## PACKAGES

### Necessary packages

```bash
sudo apt install python3
sudo apt install python3-pip
sudo apt install python3.10-venv
sudo apt-get install unzip
sudo apt-get install luarocks
sudo apt-get install cmake
sudo apt-get install ruby-dev
sudo apt install vifm
sudo apt install gh
sudo apt install sxiv
sudo pip install howdoi --upgrade
sudo pip install thefuck
sudo apt install tree
sudo apt install fzf
sudo apt install tmux
npm install -g live-server
```

</br>

## FISH

### Install fish

```bash
sudo apt-add-repository ppa:fish-shell/release-3
sudo apt-get update && sudo apt-get upgrade
sudo apt-get install fish
sudo chsh -s /usr/bin/fish
chsh -s /usr/bin/fish
```

### Install config fish

```bash
cd $HOME/.config/fish
wget https://github.com/Ruslan-Tasminsky/fish-config/blob/main/alias.fish
wget https://github.com/Ruslan-Tasminsky/fish-config/blob/main/config.fish
```

### [Install omf](https://github.com/oh-my-fish/oh-my-fish)

### [Install fisher](https://github.com/jorgebucaran/fisher)

### [Hotkeys for fish](https://github.com/jethrokuan/fzf)

### [Autopairs for fish](https://github.com/jorgebucaran/autopair.fish)

### [Theme for fish](https://github.com/IlanCosman/tide)

</br>

## NODE

### [Install nvm (node and npm)](https://github.com/derekstavis/plugin-nvm)

</br>

## NVIM

### [Neovim stable install](https://github.com/neovim/neovim/releases/tag/stable)

### [Astrovim install](https://astronvim.github.io/)

### Clone astrovim config

```bash
cd $HOME/.config/nvim/lua
git clone git@github.com:Ruslan-Tasminsky/cat-nvim-config.git user
```

</br>

## TMUX

### [Install tpm](https://github.com/tmux-plugins/tpm)

### Clone tmux config

```bash
cd $HOME
wget https://github.com/Ruslan-Tasminsky/my-tmux/blob/main/.tmux.conf
```
