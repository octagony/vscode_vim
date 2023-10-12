# Vim configuration for VSCode

## But, why?

- VSCode is an excellent code editor with many options and plugins, but you often use the mouse to navigate to the editor

- Vim (or Nvim as you prefer) has easy keyboard navigation and different modes, but setting up and configuring it can be very time consuming, especially if you are not ready to work with configuration files directly

The [VSCodeVim plugin](https://github.com/VSCodeVim/Vim) and this set of keybindings and options will combine the power plugins from VSCode with the comfort of navigation from Vim.

## Before installation

- Most of the key bindings set for VSCode copy my own key bindings for Nvim. I recommend looking at [this repository](https://github.com/octagony/dev_files) where my configuration files are stored

- If you feel you don't know enough to use Vim well, i recommended [this great article](https://betterprogramming.pub/50-vim-mode-tips-for-ide-users-f7b525a794b3) by Sebastian Carlos which details Vim best practices

## Installation

1. Install [VSCode](https://code.visualstudio.com/) or [VSCodium(my recommendation)](https://vscodium.com/) from official websites.

2. Launch the editor and complete the basic setup (install the necessary plugins, themes, icons)

3. Install [VSCodeVim plugin](https://github.com/VSCodeVim/Vim)

4. Copy keybindigs.json and settings.json files from repository to directory where the VSCode configuration files are stored. In my case it is `.config/{VSCodium,Code}/User`

5. Enjoy!

### Where to see configuration files?

Default keybinding to open the settings panel - `Ctrl + s p `. From the menu you can open user settings and default keybindigs in json format
