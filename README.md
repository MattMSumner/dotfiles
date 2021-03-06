MattMSumner dotfiles
===============

I use [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles) and
MattMSumner/dotfiles together using the `*.local` convention described in
thoughtbot/dotfiles.

Install
-------

Clone onto your laptop:

    cd ~
    git clone git://github.com/thoughtbot/dotfiles.git
    git clone git://github.com/MattMSumner/dotfiles.git dotfiles-local

Install:

    env RCRC=$HOME/dotfiles/rcrc rcup

This will create symlinks for config files in your home directory.

You can safely run `rcup` multiple times to update.

What's in it?
-------------

[git](http://git-scm.com/) configuration:

* `l` alias for tight, colored, log output.
* `cb` alias for checkout of a new branch.
* `db` alias for deletion of branches.
* `d` alias for `diff`.
* `ds` alias for `diff --cached`.
* `fuckit` alias for throwing everything away.
* My name and email.

[zsh](http://zsh.sourceforge.net/FAQ/zshfaq01.html) configuration and aliases:

* `todo` to edit my todo file, located at `~/Dropbox/todo`.
* Specify location of [Go workspace](http://golang.org/doc/code.html#GOPATH).

[tmux](http://tmux.sourceforge.net/) configuration:

* fix for copy/paste functionality with osx
* vim like selection of text
* smaller increment resizing with alt+(h,j,k,l)
* smart pane switching with ctrl+(h,j,k,l) to move between panes and vim
