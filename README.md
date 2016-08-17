# TGrep2
## fixed for macOS

This is a fork of [TGrep2](https://tedlab.mit.edu/~dr/Tgrep2/) that applies the [patches of the HLP lab blog](https://hlplab.wordpress.com/2011/02/09/compiling-tgrep2-on-an-intel-macintosh/).

I've precompiled the binary on a recent Macbook so it will probably work out of the box (`tgrep2` in the folder `TGrep2`), but in case it doesn't or you don't trust me, here's how you compile both DRUtils (the required library) and TGrep2:

    cd DRUtils
    make
    cd ../TGrep2
    make

The binary doesn't need any other files to function, so you can move it somewhere on your path (like `/usr/local/bin`)


## Copyright
TGrep2 is Copyright (C) 2001-2005, Douglas L. T. Rohde. It is available free of charge and is governed by the GNU General Public License, version 2.
