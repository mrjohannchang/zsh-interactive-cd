# zsh-interactive-cd

## Demo

![demo](demo.gif)

## Installation

1. Install [fzf](https://github.com/junegunn/fzf) by following its [installation instruction](https://github.com/junegunn/fzf#installation).

2. Download, and source `zsh-interactive-cd.plugin.zsh` in `.zshrc`:

```bash
$ mkdir -p $HOME/.zsh/plugins/zsh-interactive-cd
$ curl https://raw.githubusercontent.com/changyuheng/zsh-interactive-cd/master/zsh-interactive-cd.plugin.zsh > $HOME/.zsh/plugins/zsh-interactive-cd/zsh-interactive-cd.plugin.zsh
$ echo '# zsh-interactive-cd\nsource $HOME/.zsh/plugins/zsh-interactive-cd/zsh-interactive-cd.plugin.zsh' >> $HOME/.zshrc
$ source ~/.zshrc
```

## Usage

Press tab for completion as usual, it'll launch fzf automatically. Check fzf’s [readme](https://github.com/junegunn/fzf#search-syntax) for more search syntax usage.
