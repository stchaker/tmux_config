# tmux_config
Personal tmux configuration is hosted here. Clone to work with this environment on multiple machines. Meant for use with terminal editing via neovim.
Assuming you have already installed iterm2, ohmyzsh, and homebrew for package management.
Installation order is as follows:
  1. Clone this repository with the following command: git clone https://github.com/stchaker/tmux_config.git ~/.config/tmux
  2. Install the tmux plugin manager with the following command: git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
  3. Install neovim (usually using homebrew or another package manager)
  4. Install my neovim config at: https://github.com/stchaker/kickstart.nvim.git ~/.config/nvim
  5. Run tmux and nvim and it should install all plugins should work.

For seamless integration with themeing don't forget to install https://www.nordtheme.com/ for iterm2 or whatever terminal emulator you're using. You will also want a nerd font like: https://www.jetbrains.com/lp/mono/

In order for the debuggers to function for go and python, dont forget to install the delve debugger for go, and the debugpy package for python. 

Install plugins with tmux using control-a + I. Lazy should install neovim plugins.
