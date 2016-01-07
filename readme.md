# base16-eighties-dark for iTerm2 and ZSH

[Sublime Text Theme](https://github.com/erhankaradeniz/Base16-Eighties-Dark-iterm) Eighties Dark theme in your terminal.

This theme is an edit from the [Cobalt2 theme by Wes Bos](https://github.com/wesbos/Cobalt2-iterm). I've only changed the colors of the layout to match my preferences.

![](http://www.erhankaradeniz.com/iterm2-eighties-dark.png)

`base16-eighties-dark.itermcolors` is for anyone who uses iTerm2 and wants the colours. The `base16-eighties-dark.zsh-theme` is the prompt layout for zsh users.

They work well together! You will need to install the patched powerline font as well, which is included in this repo.

####Step-by-step installation
1. Drop the `base16-eighties-dark.zsh-theme` file in to the `~/.oh-my-zsh/themes/` directory.
2. Open up your ZSH preferences at `~/.zshrc` and change the theme variable to `ZSH_THEME="base16-eighties-dark"`.
3. In iTerm2 access the *Preferences* pane on the *Profiles* tab.
4. Under the *Colors* tab import the `base16-eighties-dark.itermcolors` file via the *Load Presets* drop-down.
5. Under the *Text* tab change the font for each type (*Regular* and *Non-ASCII*) to '**Inconsolata for Powerline**'. (Refer to the [powerline-fonts repo](https://github.com/powerline/fonts) for help on font installation.)
6. Refresh ZSH by typing `source ~/.zshrc` on the command line.
