# About

Repository with all my dotfiles.

# Install

Firstly, install [oh my zsh](https://github.com/robbyrussell/oh-my-zsh) and zsh:

```
  $ brew install zsh
```

```
  $ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

The installation script should set zsh to your default shell, but if it doesn't you can do it manually:

```
  chsh -s $(which zsh)
```

Then, run:

    git clone git://github.com/raphaeltelatim/dotfiles.git ~/.dotfiles
    ~/.dotfiles/install.sh

#### Spaceship Theme:

```
  git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"
```

#### Plugins:

    git clone git://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    git clone https://github.com/zsh-users/zsh-autosuggestions       ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions


#### Fira Code font

```
  brew tap homebrew/cask-fonts
  brew cask install font-fira-code
```
