## Sashimi

A Prompt theme for fish shell.

[![MIT License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](/LICENSE)

### Preview

<p align="center">
   <img src="https://github.com/isacikgoz/sashimi/blob/master/images/preview.png" alt="screenshot"/>
</p>

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
You can install sashimi with simply cloning the repo and link to fish prompt file.
  ```shell
  git clone https://github.com/isacikgoz/sashimi.git
  cd sashimi
  ln -s fish_prompt.fish ~/.config/fish/functions/fish_prompt.fish
  ```
  
  However, I recommend installing it via a fish shell pacakge manager;
  
* If you are using [Fisher](https://github.com/jorgebucaran/fisher):
  ```shell
  fisher add isacikgoz/sashimi
  ```
* Or, if you prefer [oh my fish](https://github.com/oh-my-fish/oh-my-fish):
  ```shell
  omf install sashimi
  ```

### Credits
This prompt is inspired from some popular themes such as:
- [robbyrussell](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme)
- [sorin](https://github.com/fish-shell/fish-shell/tree/master/share/tools/web_config/sample_prompts)
- [bobthefish](https://github.com/oh-my-fish/theme-bobthefish)
