pipeclip
========

This program pops open your `$EDITOR` or `$VISUAL`, takes whatever you
inputted into the file, and pipes it to the X clipboard.

As such, this program only works on Linux and BSD.

I've tested it on Arch Linux and FreeBSD.

Installation
------------

pipeclip is written in Haskell, so please install Haskell first:
<https://github.com/bitemyapp/learnhaskell/blob/master/install.md>.

You also need to have `xclip` or `xsel` installed.

Then,

    cabal install pipeclip

Usage
-----

    pipeclip v.0.1.0.0
    Copyright (c) 2015, Peter Harpending.
    Licensed under the FreeBSD license. See --license for info.
    
    OPTIONS
        -h,--help             Show this page
        --license             Print out the license.
        --stdout              Print output to stdout instead of piping to the clipboard.
        -t,--template EXT     Name the temporary file the editor edits tmp.EXT so that 
                              it has highlighting and stuff.
