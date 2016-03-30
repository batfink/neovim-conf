This is a simple neovim configuration.

# Installation

```bash
cd ~/.config
git clone https://github.com/teotwaki/neovim-conf.git nvim
```

Upon first launch, nvim will automatically install the plugin manager and fetch all the plugins.

# Configuration

A couple of steps are required to configure all the plugins:

```bash
pip install --user neovim
cd ~/.config/nvim/plugged/YouCompleteMe
./install.py --clang-completer
```
