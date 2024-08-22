# dotfiles

dotfiles are managed with chezmoi.

## Installation

Install homebrew.

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Install homebrew packages.

```sh
brew bundle
```

Install alacritty themes.

```sh
mkdir -p ~/.config/alacritty/themes
git clone https://github.com/alacritty/alacritty-theme ~/.config/alacritty/themes
```

Apply dotfiles.

```sh
chezmoi init --apply stefafafan
```
