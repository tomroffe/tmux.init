# tmux.init

## install tmux

```bash
brew install tmux
mkdir -p ~/.config/tmux ~/.tmux/plugins
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
git clone git@github.com:tomroffe/tmux.init.git/ ~/.config/tmux
tmux source .config/tmux/tmux.conf

```
