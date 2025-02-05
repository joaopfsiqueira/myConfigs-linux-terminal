# Configs

- I create this repository just for centralize all my configs.

## OhMyZSH

## Installation

```
Open terminal
```

```
apt-get install zsh
```

```
chsh -s $(which zsh)      (zsh be the system default command interpreter)
```

```
apt install curl
```

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

```
restart terminal.
```

# Themes

## Spaceship

```
git clone https://github.com/spaceship-prompt/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt" --depth=1
```

```
ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"
```

```
vi ~/.zshrc
press i
And change ZSH_THEME="spaceship"
press esc

:wq
enter
```

```
source ~/.zshrc - Reload zsh
```

# Aditional Plugins

## zsh-syntax-highlighting

```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

## zsh-autosuggestions

```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

## aws

```
https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/aws
```

## kubernetes

```
https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/kubectl
```


## zsh-fast-syntax-highlighting plugin

```
git clone https://github.com/zdharma-continuum/fast-syntax-highlighting.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/plugins/fast-syntax-highlighting
```

## zsh-autocomplete plugin

```
git clone --depth 1 -- https://github.com/marlonrichert/zsh-autocomplete.git $ZSH_CUSTOM/plugins/zsh-autocomplete
```

### End

```
vi ~/.zshrc

press i

And change plugins=(git aws kubectl zsh-autosuggestions zsh-syntax-highlighting fast-syntax-highlighting zsh-autocomplete)

press esc

:wq

enter

source ~/.zshrc
```
