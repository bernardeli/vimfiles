# DEPRECATED 

Moved my vimfiles to my [dotfiles repo](https://github.com/bernardeli/dotfiles) so I can properly manage it all with [fresh](https://github.com/freshshell/fresh)


# Vimfiles

## How to use these vim configs

Clone this repository into your home directory as `~/.vim` and then install the plugins. Such as:

    git clone git://github.com/bernardeli/vimfiles.git ~/.vim
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
    ln -s ~/.vim/vimrc ~/.vimrc
    cp ~/.vim/fonts/Monaco+for+Powerline.otf ~/Library/Fonts/

In order to install / update the plugins, start vim and then run:

    :PluginInstall

**Optional:**

Install jshint in order to review your javascript files:

    npm install -g jshint

Get named arguments lint working:

    sudo ln -s /Users/ric/.rbenv/shims/ruby /usr/bin/ruby

## Thanks

Used a lot of [Lucas Caton](http://github.com/lucascaton/vimfiles)'s vimfiles.
Big thanks to him :-)

## License

MIT
