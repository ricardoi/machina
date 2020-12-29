# Programs

Contains:
- R with OpenBLAS and essential packages.
- Configuretion for tmux, neovim, and zsh.
- Cousine font with nerd fonts.

# Requirement for macOS
- command line tools

```shell
# command line tools
sudo xcode-select --install
```

# Usage macOS 

Following commands will clone the repository, install depenecies and make symbolic links.

```shell
# clone this repo
git clone git://github.com/ricardoi/machina ~/machina

cd dotfiles

# install dependencies and make symbolic links
sh setup.sh
```


## Installing all R packages of interest
```bash
# executing R installation with packages for: Virome Community Ecology and Evolution
sh Rpkg.sh install
```
< Rpkg.sh executes Rpkgs.r that reads the Rpkgs_list [list updated December 2020](https://github.com/ricardoi/machina/blob/master/Rpkgs_list) >
