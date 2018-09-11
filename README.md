## Sashimi

A Prompt theme for fish shell.

[![Oh My Fish](https://img.shields.io/badge/Framework-Oh_My_Fish-blue.svg)](https://github.com/oh-my-fish/oh-my-fish) [![MIT License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](/LICENSE)

### Features
- sleek
  - prints only the parent instead of pwd
- git support
  - shows dirty status
  - ahead/behind info
  - discourages to work on master branch
- informative when required
  - shows error returns along with painting the prompt to red

### Install
if you have [oh my fish](https://github.com/oh-my-fish/oh-my-fish) framework, you can simply:
```bash
omf install sashimi
```
or you can manually:
```bash
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
