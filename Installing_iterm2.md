**How to install Iterm2**
-
1. Install iterm2 from [here](https://www.iterm2.com/)
2. Install homebrew from [here](https://brew.sh/)
3. Get zsh from [here](https://gist.github.com/kevin-smets/8568070)

   - run this to install _oh-my-zsh_,`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
   - and install _Powerlevel10k_, run this `git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k`
   Then edit your `~/.zshrc` and set `ZSH_THEME="powerlevel10k/powerlevel10k"`
   - To run the configuration again, run `p10k configure`
   - In normal Mac terminal change the font from _**SF Mono**_ to _**MesloLGS NF**_
   - More info on [powerlevel10k](https://github.com/romkatv/powerlevel10k/blob/master/README.md#instant-prompt)
   - Install a patch font [Source Code Pro & Font Awesome](https://github.com/Falkor/dotfiles/blob/master/fonts/SourceCodePro%2BPowerline%2BAwesome%2BRegular.ttf)
4. iTerm2 material design [link](https://github.com/MartinSeeler/iterm2-material-design)
5. To remove right side prompt element edit `~/.p10k.zsh` and remove everything inside the parentheses at `typeset -g POWERLEVEL9K_RIGHT_PROMPT_ELEMENTS=()`