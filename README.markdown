git-fu
======

Calculates your git-fu based on the reflog of your git repository.

Installation
============

Create a symlink to the git-fu script.

    $ sudo ln -s `pwd`/git-fu /usr/local/bin/git-fu

Alternatively, copy git-fu to a location on your path. E.g. if you have a private bin folder:

    $ cp git-fu ~/bin/

Usage
=====

cd into a git repository, then run git-fu from the shell with no arguments.

    $ cd my_git_repository
    $ git-fu

It will give you a score.

    Your git-fu: 650
