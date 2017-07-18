# .tmux

My terminal multiplexer stack for macOS.

## Installation

1. Install latest `tmux` from MacPorts:

        $ sudo port install tmux

2. Install pasteboard

        $ sudo port install tmux-pasteboard

  See [macOS pasteboard fix for Vim on tmux](http://tekkie.flashbit.net/macos/howto/macos-pasteboard-fix-vim-tmux) for more information.

3. Clone this repo

        $ git clone https://github.com/ain/.tmux.git ~/.tmux

4. Symlink `tmux` configuration to user namespace

        $ ln -s ~/.tmux/.tmux.conf ~/.tmux.conf

5. Update plugins

        $ cd ~/.tmux
        $ ./update
