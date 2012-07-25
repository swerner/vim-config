# To Install

(Re)move ~/.vim and ~/.vimrc if you have them already, and run:

    git clone git@github.com:STAdmin/vim-config.git ~/.vim
    cd ~/.vim
    git submodule update --init
    ln -s ~/.vim/vimrc ~/.vimrc
    
Additional instructions for installing tmux-config related items here: https://github.com/SideTour/tmux-config/blob/master/README.md
The submodule is already installed. Just add the symlink and bash profile line.

# Updating

As long as your checkout is kept clean, you can easily update, rebase your local changes and update submodules with:

    cd ~/.vim && git pull --rebase ; git submodule update ; cd -