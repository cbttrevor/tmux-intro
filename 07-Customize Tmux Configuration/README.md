## Learning Objectives

### Configuration Files

Tmux loads configurations from two filesystem locations:
If both files exist, the the system configuration is loaded first, and the user configuration is loaded second.

1. `/etc/tmux.conf`
1. `~/.tmux.conf`

### Configure Tmux Interactively

In addition to configuring tmux at startup time using configuration files, you can also configure tmux interactively using the command prompt.
To access the command prompt in tmux, use the default keyboard shortcut `<prefix> + :`

### Configuration Options

* There are four different levels of configuration options in tmux:
  * Server
  * Session
  * Window
  * Pane
* The `set-option` (abbreviated `set`) command applies to the specified session
* The `set-window-option` (abbreviated `setw`) command applies to the specified window