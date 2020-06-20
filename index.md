## TMUX Cheat Sheet

TMUX is a terminal multiplexer. It allows multiple terminal sessions to be accessed simultaneously in a single window. It is useful for running more than one command-line program at the same time.

### Installing

1) On debian based machine: sudo apt install tmux

2) On Mac: brew install tmux



### Panes

1) Split into vertical: Ctrl-B + %

2) Split into horizontal: Ctrl-B + "

3) Switch between panes: Ctrl-B + arrow

4) Exit a pane: Ctrl-D (or "exit")


### Windows

1) Create new window: Ctrl-B + C

2) Switch to window: Ctrl-B + number

3) Rename window: Ctrl-B + ,

4) Exit window: Ctrl-D (or "exit")


### Sessions

1) Detach session: Ctrl-B + D

2) List sessions: tmux ls
3) Rename session: tmux rename-session -t $target $newname

4) Re-attach to session: tmux attach -t $target

5) Create new named session: tmux new -s $name

6) Delete session: tmux kill-session -t $target
