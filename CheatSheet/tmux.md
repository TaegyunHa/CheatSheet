# TMUX
## Install

mac
```
brew install tmux
```
linux
```
apt-get install tmux
```
## tmux layers
```
Session Layer
|- Window Layer
   |- Pane Layer
```

## Command line

**Start**
```
tmux
```
**Create Session**
```
tmux new -s <sessionName>
```
**List All Sessions**
```
tmux ls
```
**Attach to the latest session**
```
tmux a
```
**Attach to the target session `<sessionName>`**
```
tmux a -t <sessionName>
```
**Kill the most recent session**
```
tmux kill-session
```
**Kill the session `<sessionName>`**
```
tmux kill-session -t <sessionName>
```
Kill all
```
tmux kill-server
```

## Basic Commands

| Command               | Description                 |
| --------------------- | --------------------------- |
| `Ctrl+b` `d`          | Detach from current session |
| `Ctrl+b` `c`          | Create new window           |
| `Ctrl+b` `&`          | Close window                |
| `Ctrl+b` `x`          | Close pane                  |
| `Ctrl+b` `%`          | Split window horizontally   |
| `Ctrl+b` `"`          | Split window vertically     |
| `Ctrl+b` `n`          | Switch to next window       |
| `Ctrl+b` `p`          | Switch to prev window       |
| `Ctrl+b` `<num>`      | Switch window by index      |
| `Ctrl+b` `<arrow>`    | Switch pane by arrow        |
| `Ctrl+b` `q<num>`     | Switch pane by index        |
| `Ctrl+b` `w`          | List sessions               |
| `Ctrl+b` `s`          | List windows                |
| `Ctrl+b` `:<command>` | Execute command             |

## Copy & Paste

| Command      | Description |
| ------------ | ----------- |
| `Ctrl+b` `[` | Copy        |
| `<Space>`    | Start copy  |
| `<Enter>`    | Finish copy |
| `Ctrl+b` `]` | Paste       |
