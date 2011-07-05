# My MacOS Emacs setup (Aquamacs)

## Install

    $ cd ~
    $ git clone git://github.com/jbpros/emacs-setup.git .emacs.d
    $ cd .emacs.d
    $ git submodule update --init --recursive
    $ cd auto-complete
    $ emacs -batch -l etc/install.el

Tell the auto-complete installer to install in `~/.emacs.d/auto-complete-bin`.

You'll then need to:

* Set the colors used by Magit
