# ⚙️ Foreground and Background Processes in Linux

## Commands Used

- `&` (run process in background)
- `jobs` (list background jobs)
- `Ctrl + C` (terminate process)
- `Ctrl + Z` (suspend process)
- `fg` (bring process to foreground)
- `bg` (resume process in background)

## Description

- **Foreground** → process runs in the terminal and blocks it until completion
- **Background** → process runs without blocking the terminal

## Examples

- `sleep 1000 &` → runs process in background
- `sleep 1000 && echo "done" &` → executes sequence in background
- `jobs` → lists active/suspended background jobs
- `fg %1` → brings job with ID 1 to foreground
- `bg %1` → resumes job in background
- `Ctrl + C` → stops a running process
- `Ctrl + Z` → pauses the current process

## Key Learnings

- Background processes allow multitasking in the terminal
- `&` is essential for long-running commands
- `jobs`, `fg`, and `bg` help manage process execution
- `Ctrl + Z` pauses, `bg` resumes without blocking
- Efficient process management improves productivity and workflow