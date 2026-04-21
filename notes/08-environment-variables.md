# 🌍 Environment Variables in Linux

## Commands Used

- `echo $VARIABLE` (read variable value)
- `export` (create global environment variables)
- `env | less` (list environment variables)
- `cat ~/.bashrc` (verify configuration)
- `>> ~/.bashrc` (persist variables)

## Description

- Environment variables store system-wide configuration values
- Accessed using `$VARIABLE_NAME`
- Can be local (session-only) or global (available to other processes)

Common variables:
- `PWD` → current working directory
- `PATH` → directories where executables are searched
- `LANGUAGE` → system language and encoding
- `SHELL` → current shell being used

## Examples

- `echo $SHELL` → shows current shell (e.g. /bin/bash)
- `myvar="hello"` → creates a temporary variable
- `echo $myvar` → prints the value
- `export myvar="hello"` → makes it available globally
- `echo 'export myvar="hello"' >> ~/.bashrc` → persists the variable
- `source ~/.bashrc` → reloads configuration

## Key Learnings

- Environment variables control system and application behavior
- Temporary variables only exist in the current session
- `export` makes variables accessible to child processes
- Persistent variables must be added to shell config files like `.bashrc`
- `PATH` is one of the most critical variables for command execution
- Proper use of variables improves automation and configuration management