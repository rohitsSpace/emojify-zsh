
## Emojify-Zsh Theme

Emojify-zsh is a [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) theme that adds emojis to your zsh terminal.
Emojify will display a random emoji for every command you type, as of now Emojify Support More than 350 Emojis. If you want me to add more emojies in then create an issue and assign it to me :wink:.


### Prerequisites

* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

### Setup

1. Download Emojify-zsh theme as a oh-my-zsh custom theme:

```bash
 $ mkdir -p $ZSH_CUSTOM/themes && curl -o $ZSH_CUSTOM/themes/emojify_zsh.zsh-theme https://raw.githubusercontent.com/akabiru/Emojify-zsh/develop/emojify_zsh.zsh-theme
```

2. Set `ZSH_THEME` to `emojify_zsh` in your `~/.zshrc`.

```bash
$ vim ~/.zshrc
 # ZSH_THEME='emojify_zsh'
```

3. Reload your zsh configuration and Voila! Emojify is watching over you. :sunglasses:

```bash
$ source ~/.zshrc
```

### Contributing

Feel free to contribute, even if it's to add an emoji. :wink: Just fork it :fork_and_knife: and raise a pull request.

### Credits

This projects borrows from [Robby Russell's](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/robbyrussell.zsh-theme) theme.
Not forgetting [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) itself. :smile:
