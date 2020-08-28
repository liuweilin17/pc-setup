## Terminal Setup - Mac

This is the key parts in the setup, since terminal is the one of the most frequently used environment for SDE

* Dracula

  Dracula](https://draculatheme.com/terminal/) is the darm theme for Terminal.app

* ZSH

  [Zsh](http://zsh.sourceforge.net/) is the built on `bash`, configuration in `~/.zshrc`

  ZSH has [too many features](https://github.com/hmml/awesome-zsh) to list here, some just minor improvements to Bash, but here are some of the major ones:

  - **Automatic cd:** Just type the name of the directory
  - **Recursive path expansion:** For example “/u/lo/b” expands to “/usr/local/bin”
  - **Spelling correction and approximate completion:** If you make a minor mistake typing a directory name, ZSH will fix it for you
  - **Plugin and theme support:** ZSH includes many different plugin frameworks

  Plugin and theme support is probably the coolest feature of ZSH and is what we’ll focus on here.

* Oh-my-zsh

  [Oh My Zsh](Oh My Zsh is a delightful, open source, community-driven framework for managing your Zsh configuration.) is a delightful, open source, community-driven framework for managing your Zsh configuration.

  * [Powerlevel9k](https://github.com/Powerlevel9k/powerlevel9k#installation) is a theme for ZSH which uses [Powerline Fonts](https://github.com/powerline/fonts).

    NOTE: we need to install Poweline Fonts first, then choose `Meslo LG M DZ Regular for Powerline` in **Preferences - Profiles - Font**

* Tmux

  [tmux](https://github.com/tmux/tmux/wiki) is a terminal multiplexer. It lets you switch easily between several programs in one terminal, detach them (they keep running in the background) and reattach them to a different terminal.

  * Intall tmux

    ```
    brew install tmux
    ```

  * Add [tmux plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/tmux) in oh-my-zsh.

    ```
  plugins=(
      git
      tmux
    )
    ```
  * Reference
    [tmux plugin shortcut](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/tmux)
    
    [tmuxcheatsheet](https://tmuxcheatsheet.com/)

* Vim

   provides abundant vim plugins, simply install it by following Installation section in [My Vim Setup](https://github.com/liuweilin17/dot-vimrc)

  
