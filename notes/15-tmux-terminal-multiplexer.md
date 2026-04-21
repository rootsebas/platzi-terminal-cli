# 🧩 Tmux (Terminal Multiplexer)

## Commands Used

- `tmux` (start tmux session)
- `tmux ls` (list sessions)
- `tmux attach` (attach to session)
- `exit` / `Ctrl + D` (close pane)

## Description

- Tmux allows multiple terminal sessions in one window
- Uses a **prefix key** (default: `Ctrl + B`) to trigger commands
- Supports panes, windows, and persistent sessions

## Basic Controls (Prefix: Ctrl + B)

### Panes

- `%` → split vertically
- `"` → split horizontally
- Arrow keys → move between panes
- `exit` or `Ctrl + D` → close pane

### Windows

- `c` → create new window
- `number` → switch between windows
- `,` → rename window

## Installation

- Linux → `sudo apt install tmux`
- macOS → `brew install tmux`

## Examples

- `tmux` → start a new session
- `tmux ls` → list active sessions
- `tmux attach` → reconnect to a session

## Key Learnings

- Tmux enables multitasking in a single terminal
- Panes and windows help organize workflows
- Sessions persist even if terminal is closed
- Ideal for remote servers and long-running tasks
- Greatly improves productivity in CLI environments