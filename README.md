# Nvim 248

## Table of contents

- [Preferences](#Preferences)
- [Package to install](#Packages)

## Preferences

- Upgrade packages

```bash

pkg upgrade

```

### Packages

- Install these packages

```sh

pkg install clang python neovim ncurses-utils nodejs-lts ctags fd git ripgrep fzf ranger fontconfig-utils

```

- Clean system

```sh

apt autoremove

```

- Upgrade pip

```sh

pip install pip --upgrade

```

- Install pipenv

```sh

pip install pipenv

```

- Create virtual environment for neovim only

```sh

mkdir -p ~/neovim_env && cd ~/neovim_env

```

### Install required libries

```sh

pipenv install jedi pynvim pylint isort flake8 yapf

```

### Optional ( Nerd fonts Hack )

> Move fonts to `~/.local/share`
> Create `~/.local/share` if it does not
> exist Eg. `mkdir -p ~/.local/share/`

### Regenerate you cache and index it

```sh

fc-cache -f -v

```

### Verifully if font was successfully generated

```sh

fc-list | grep "Hack"

```
