## Learning Objectives

You can use the `tmuxp` open source utility to snapshot and restore your tmux sessions.
This is especially useful if you need to reboot your system, and thereby terminate your tmux sessions.
After restarting your Linux server, you can pick up where you left off by restoring your tmux session configurations.

### Install Tmuxp

```bash
pip3 install tmuxp
```

### Using Tmuxp

Freeze a tmux session

```bash
tmuxp freeze
```

Restore a tmux session

```bash
tmuxp load 0
```