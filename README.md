# nvim
## Install nvim
```
sudo add-apt-repository ppa:neovim-ppa/unstable
sudo apt update
sudo apt install neovim
```
## Install build-essentils
```
sudo apt-get install build-essential
```

## Create *.config* directory
### Clone this repository in configuration directory
  - ssh-keygen -t ed25519 -C "your_email@example.com"
  - ~/.ssh/id_ed25519.pub
  
## Clone Packer
```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

## Go to packer.lua
  - :so
  - :PackerSync
  
## Install grep
