# 💻 Terminal Customization (Zsh, Oh My Zsh & Powerlevel10k)

## Commands Used

- `sudo apt install zsh` (install Zsh)
- `sh -c "$(curl -fsSL ...)"` (install Oh My Zsh)
- `git clone` (install Powerlevel10k theme)
- `source ~/.zshrc` (reload configuration)

## Description

- Zsh is an advanced shell alternative to Bash with better features
- Oh My Zsh enhances Zsh with plugins, themes, and productivity tools
- Powerlevel10k is a highly customizable and fast theme for Zsh

## Installation Steps

### Zsh

- `sudo apt install zsh` → install Zsh
- Set it as default shell (optional but recommended)

### Oh My Zsh

- `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` → install framework

### Powerlevel10k

- `git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k`
- Edit `~/.zshrc`:
  - `ZSH_THEME="powerlevel10k/powerlevel10k"`
- `source ~/.zshrc` → apply changes

## Fonts

- Install **Meslo Nerd Font** for proper icons and symbols display

## Key Learnings

- Zsh provides better autocompletion and customization than Bash
- Oh My Zsh simplifies configuration with plugins and themes
- Powerlevel10k improves terminal UX with rich visual information
- Customizing your terminal boosts productivity and workflow clarity
- Fonts are required to fully enable visual features