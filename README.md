# 🏠 Dotfiles

This repository contains my personal dotfiles, and it is managed by [chezmoi](https://www.chezmoi.io/).

## 📖 Quick Reference Guide

Initialise chezmoi's source directory with my dotfiles stored in GitHub (this does not apply any changes):
```
chezmoi init jmgq
```

Add a new file:
```
chezmoi add .some-dot-file
```

Edit an existing file:
```
chezmoi edit .some-dot-file
```

See a quick summary of the files that would change if we applied the changes:
```
chezmoi status
```

Display the difference between the desired state and the actual state of the dotfiles:
```
chezmoi diff
```

Apply changes:
```
chezmoi apply
```

Jump to the chezmoi directory (in a new subshell):
```
chezmoi cd
```

Pull the latest version from the source repo and apply any changes:
```
chezmoi update
```

You can pass the `--dry-run` flag to any command to simulate its output without actually running it.

Similarly, the `--verbose` option is globally available.

In order update the GitHub repository with any local changes, you need to go to the chezmoi directory and use Git's `add`, `commit` and `push` commands.
