# cute tmux (ﾉ◕ヮ◕)ﾉ*:・ﾟ✧

## Installation

### Install manually

1. Clone repo to local machine:

```sh
git clone https://github.com/cshaver/tmux-cute.git ~/.tmux-cute
```

2. Source desired theme in your `~/.tmux.conf`:

```.tmux.conf
source-file "${HOME}/.tmux-cute/cute.tmuxtheme"
```

### Install using [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

1. Add plugin to the list of TPM plugins in `.tmux.conf`:

        set -g @plugin 'cshaver/tmux-cute'

2. Hit `prefix + I` to fetch the plugin and source it. The plugin should now be working.
