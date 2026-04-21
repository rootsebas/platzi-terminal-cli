# 📊 Process Monitoring and Management in Linux

## Commands Used

- `ps aux` (list running processes)
- `grep` (filter processes)
- `top` (real-time process monitoring)
- `htop` (interactive process viewer)
- `kill` (terminate processes)

## Description

- `ps aux` → shows a snapshot of all running processes
- `ps aux | grep name` → filters processes by name
- `top` → displays real-time system and process activity
- `htop` → improved, interactive version of `top`
- `kill` → sends signals to terminate processes by PID

## Examples

- `ps aux` → list all processes with details (CPU, memory, PID)
- `ps aux | grep sleep` → find a specific process
- `top` → monitor processes dynamically
- `htop` → interactive monitoring (search, tree view, UI)
- `kill -9 1234` → force kill process with PID 1234

## Key Learnings

- `ps` provides a static snapshot; `top/htop` provide real-time monitoring
- PID (Process ID) is essential for managing processes
- `grep` helps locate specific processes quickly
- `htop` offers better usability and visualization than `top`
- `kill -9` forcefully terminates processes (use with caution)
- Monitoring processes is key for performance tuning and debugging