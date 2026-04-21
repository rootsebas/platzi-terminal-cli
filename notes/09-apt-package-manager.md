# 📦 APT Package Manager in Linux

## Commands Used

- `sudo apt update` (update package list)
- `sudo apt upgrade` (upgrade installed packages)
- `sudo apt install` (install a package)
- `sudo apt remove` (remove a package)
- `sudo apt purge` (remove package + config)
- `apt show` (view package info)
- `apt list --upgradeable` (check available updates)

## Description

- APT (Advanced Package Tool) is the package manager used in Debian-based systems like :contentReference[oaicite:0]{index=0} and :contentReference[oaicite:1]{index=1}
- It allows you to install, update, and remove software from the terminal
- Works with repositories (remote sources of packages)

Other package managers:
- `DNF / YUM` → Red Hat / Fedora
- `Pacman` → Arch Linux

## Examples

- `sudo apt update` → refresh package list
- `sudo apt upgrade` → update installed packages
- `sudo apt install neofetch` → install a package
- `neofetch` → run installed program
- `sudo apt remove neofetch` → remove package
- `sudo apt purge neofetch` → remove package and configuration
- `apt show neofetch` → display package details
- `apt list --upgradeable` → list pending updates

## Key Learnings

- APT simplifies software management in Linux
- Always run package operations with `sudo`
- Updating involves two steps: `update` (fetch info) and `upgrade` (apply changes)
- `purge` removes everything, including configs (cleaner uninstall)
- Understanding package managers is essential across Linux distributions