## Sashimi

A Prompt theme for fish shell.

[![Oh My Fish](https://img.shields.io/badge/Framework-Oh_My_Fish-blue.svg)](https://github.com/oh-my-fish/oh-my-fish) [![MIT License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](/LICENSE)

### Features
- Compatible with Fish 3.0
- Sleek
  - displays only the parent dir instead of the whole working dir
- Git Support
  - shows clean/dirty status
  - shows branch ahead/behind info
  - discourages working on master branch
- Informative When Required
  - shows error returns along with painting the prompt to red

### Install
* if you have [oh my fish](https://github.com/oh-my-fish/oh-my-fish) framework, you can simply run:
  ```shell
  omf install sashimi
  ```
* if you prefer [Fisher](https://github.com/jorgebucaran/fisher):
  ```shell
  fisher add isacikgoz/sashimi
  ```
* or manually:
  ```shell
  git clone https://github.com/isacikgoz/sashimi.git
  cd sashimi
  ln -s fish_prompt.fish ~/.config/fish/functions/fish_prompt.fish
  ```

### Preview
![screenshot](images/preview.png)

### Credits
This prompt is inspired from some popular themes such as:
- [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme)
- [sorin](https://github.com/fish-shell/fish-shell/tree/master/share/tools/web_config/sample_prompts)
- [bobthefish](https://github.com/oh-my-fish/theme-bobthefish)
