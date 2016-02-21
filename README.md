# Shit

Display images in your terminal no matter the terminal (at least 256 colors).


## Story

Once upon a time I was looking for something that would allow me to see an
image in the terminal, specifically via ssh, and the only tool I found was
a small perl script with a wierd name [here](http://askubuntu.com/a/290602).

The code wasn't on github, so I had a chat with the author who kindly let me
publish it.

Note: This was some time ago and the original link to his code is dead :(.

Original Code: http://antipathy.nonserviam.net/utilities/shit

[Video Demo](https://www.youtube.com/watch?v=sESMYVeJhKA) (Not made by me!)


## How to install:

At the moment this script was only tested on Ubuntu and Arch Linux.

Copy the script to your `bin` directory (that should be in your `$PATH` and
install the following required perl modules.

    perl -MCPAN -Mlocal::lib -e 'CPAN::install(Term::Size)'

### Arch linux

    sudo pacman -S perl-local-lib

### Ubuntu

    sudo apt-get install libimage-magick-perl
