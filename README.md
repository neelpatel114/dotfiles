# dotfiles

Personal shell configuration for macOS with zsh, Oh My Zsh, and Powerlevel10k.

## Quick Install

```bash
git clone https://github.com/YOUR_USERNAME/dotfiles.git ~/dotfiles
cd ~/dotfiles
./install.sh
```

## What's Included

- **zshrc** - Zsh config with Oh My Zsh, plugins, and PATH setup
- **dircolors** - Custom LS_COLORS for black terminal backgrounds (Rust/C/Python dev)
- **p10k.zsh** - Powerlevel10k prompt configuration

## LS Colors

Optimized for coding with color-coded file types:
- `.rs` - bold yellow (Rust)
- `.c/.h` - bold cyan (C)
- `.py` - bold blue (Python)
- `.json/.toml/.yaml` - green (config)
- `.md/.txt` - white (docs)
- Build artifacts - dim gray

## Dependencies (auto-installed)

- Homebrew
- GNU coreutils (for `gls`)
- Oh My Zsh
- zsh-autosuggestions
- zsh-syntax-highlighting
- Powerlevel10k
