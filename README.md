# To Install

(Re)move ~/.vim and ~/.vimrc if you have them already, and run:

    git clone git@github.com:swerner/vim-config.git ~/.vim
    cd ~/.vim
    git submodule update --init
    ln -s ~/.vim/vimrc ~/.vimrc
    
## tmux.conf Installation
If you have installed this repo as a Vim plugin:

    ln -s ~/.vim/bundle/tmux-config/tmux.conf ~/.tmux.conf

Otherwise symlink, copy the file, or copy its contents to ~/.tmux.conf

# Updating

As long as your checkout is kept clean, you can easily update, rebase your local changes and update submodules with:

    d ~/.vim && git pull --rebase ; git submodule update ; cd -
