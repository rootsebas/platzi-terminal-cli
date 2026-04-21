# 🍺 Homebrew Package Manager (macOS)

## Commands Used

- `/bin/bash -c "$(curl -fsSL ...)"` (install Homebrew)
- `brew --version` (verify installation)
- `brew search` (search packages)
- `brew info` (package details)
- `brew install` (install package)
- `brew list` (list installed packages)
- `brew update` (update Homebrew)
- `brew upgrade` (upgrade packages)
- `brew uninstall` (remove package)
- `brew cleanup` (clean unused files)

## Description

- Homebrew is a package manager for :contentReference[oaicite:0]{index=0}
- Allows installing and managing software via terminal
- Similar concept to APT in Linux systems

## Examples

- `brew --version` → verify installation
- `brew search neofetch` → search for a package
- `brew info neofetch` → get package details
- `brew install neofetch` → install a package
- `brew list` → show installed packages
- `brew update` → update Homebrew itself
- `brew upgrade` → upgrade all installed packages
- `brew uninstall neofetch` → remove a package
- `brew cleanup` → remove unused files

## Key Learnings

- Homebrew simplifies software management on macOS
- Commands are intuitive and similar to Linux package managers
- `update` updates Homebrew, `upgrade` updates packages
- Always verify packages before installing (security best practice)
- Useful for developers working across macOS and Linux environments