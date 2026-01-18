# Dotfiles and Aliases (Ubuntu / WSL)

This doc covers simple shell customization inside Ubuntu (WSL), including
aliases, PATH tweaks, and a basic “bootstrap” install list.

---

## Where these settings live

Most user shell customization goes in:

- `~/.bashrc` (interactive bash sessions)
- `~/.profile` (login shells / environment vars)

If you use Zsh, you’ll use `~/.zshrc` instead.

---

## useful aliases

Edit your bash config:

```bash
nano ~/.bashrc

alias ll='ls -lah'
alias c='clear'

alias gs='git status'
alias ga='git add -A'
alias gc='git commit'
alias gp='git pull'
alias gph='git push'

alias dev='cd ~/dev'
