## Learning Objectives

Start a new session using the `tmux new-session` command.
You can also abbreviate this to just `tmux new`.

* Detach the "active" client using `<prefix> + d`
* Remotely detach clients from tmux server using `tmux detach-client`
* Rename the current session using `<prefix> + $` (same as `CTRL + B, SHIFT + 4`)
* List out the currently running sessions using `tmux list-sessions`
  * NOTE: You can run this inside or outside tmux

### Connect Multiple Clients to the Same Session

1. Create a new tmux session
1. Attach a second, separate window
1. Resize one of the windows larger than the other
1. Notice the dead space outside the tmux window
1. Attach a new client with the `-d` option to detach other clients
1. Everything that is typed as input, or emitted as output, is replicated on both clients

## Questions We'll Answer

* How do I detach from a session and return to my root shell?
* How do I detach other clients connected to the same session?
* How do I kill an entire tmux session?
