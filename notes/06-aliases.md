# 🏷️ Aliases in Linux

## Commands Used

- `alias` (list or create aliases)
- `alias name='command'` (create temporary alias)
- `echo $SHELL` (check current shell)
- `>> ~/.bashrc` (persist aliases)
- `source ~/.bashrc` (reload configuration)

## Description

- `alias` → displays all current aliases in the system
- `alias name='command'` → creates a shortcut for a command (temporary)
- `echo $SHELL` → shows which shell you are using (bash, zsh, etc.)
- `>> ~/.bashrc` → appends alias configuration to make it permanent
- `source ~/.bashrc` → reloads the shell configuration without restarting

## Examples

- `alias cls='clear'` → creates a shortcut to clear the terminal
- `alias ll='ls -la'` → simplifies a commonly used command
- `echo "alias cls='clear'" >> ~/.bashrc` → makes the alias persistent
- `source ~/.bashrc` → applies changes immediately

## Key Learnings

- Aliases improve productivity by shortening long or repetitive commands
- Temporary aliases only exist during the current session
- Persistent aliases must be stored in shell config files like `.bashrc` or `.zshrc`
- You can customize your terminal environment based on your workflow
- Aliases can simplify complex commands or combine multiple actions