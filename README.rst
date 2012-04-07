About
-----

`my.tmux.conf` is my experience of tmux multiplexer.

Installation
------------

store .tmux.conf in your home directory

in .profile conf

    # ryan 256 color support
    if [ -e /lib/terminfo/x/xterm-256color ]; then
        export TERM='xterm-256color'
    else
        export TERM='xterm-color'
    fi

in .vimrc

    set term=screen-256color

Getting started
---------------

- replace Ctrl+b by Ctrl+q
- alt+directions navigates through panes (Alt+Right, Alt+Left, etc ...)
