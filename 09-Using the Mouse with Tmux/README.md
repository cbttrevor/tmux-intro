## Learning Objectives

Sometimes using the mouse with tmux can be useful. 
For example, you can do things like select an active pane, resize panes, and select the active window.
You can also use the scroll wheel to scroll through terminal history. 

If you want to enable mouse support in tmux, check which version of tmux you're running first.
As of tmux version 2.1, the configuration syntax has been simplified to a single mouse setting.

```
set-option -g mouse on
```

If you're running an earlier version of tmux, you can [enable mouse options individually](https://stackoverflow.com/questions/11832199/tmux-set-g-mouse-mode-on-doesnt-work).

```
set-option -g mouse-resize-pane on
set-option -g mouse-select-pane on
set-option -g mouse-select-window on
set-option -g mode-mouse on
```