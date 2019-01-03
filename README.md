# title-tab zsh (ubuntu)

> This plugin sets the tab title to `current folder (git-branch)` if you're on a git repository or `current folder` if you're not.

![title tab working](http://i.imgur.com/9nNCNIT.png)

## Installing

## Zplugin

```bash
zplugin light cristovao-trevisan/title-tab
```

## Oh-my-zsh

1. Clone this repository to `/path/to/.oh-my-zsh/custom/plugins` (usually it is on `~/.oh-my-zsh`)

  ```bash
  $ git clone git@github.com:romulomachado/title-tab.git ~/.oh-my-zsh/custom/plugins
  ```

2. Find where your zsh plugins are on the ```.zshrc``` file and add ```title-tab``` to the list.

  ```bash
  plugins=(... title-tab)
  ```

4. Run ```source .zshrc```.

  ```bash
  $ source ~/.zshrc
  ```

  Or if you use ```zsh_reload```:

  ```bash
  $ src
  ```

