# Mac Development Environment Setup

This repository provides my default mac environment setup. 

This is forked from [Chris Dail's](https://github.com/chrisdail/mac-setup) project.

## Prerequisites

The Xcode commandline tools are required to install Homebrew. You can install them by running:

```
xcode-select --install
```

## Install

Run the setup script. This will:

* Install default `dotfiles` into user home directory. These are installed with symbolic links so any changes to these files will be reflected in the `mac-setup` repo.
* Install homebrew
* Install brew apps, casks, fonts (from `Brewfile`)
* Set shell as Fish
* Install some VS Code extensions using their CLI
* Set a super high key repeat rate
* Set diffmerge as git difftool

To install, clone the repo and run `./setup`:

```
git clone https://github.com/jadnhm/mac-setup.git ~/code/mac-setup
cd ~/code/mac-setup
./setup
```

## Optional Manual Steps

Mouse Acceleration fix is located in the `misc` directory. 
http://triq.net/mac/mouse-acceleration
