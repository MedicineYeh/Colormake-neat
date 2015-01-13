Colormake - Clean Version
---------

This is a simple wrapper for making the output from make easier to read
(more colorful), and errors easier to find in messy compilations.  It was
inspired by Micheal T. Babcock's excellent logcolorize program.

To make the compilation of a big project clean and nice to debug. 
This repo aims to remove unnecessary colors and make it clean and pretty.

![Sample Image](/snapshot42.png?raw=true "Sample Image")
Files
-----

    colormake.pl   A perl filter, which colorizes make's output.
    colormake      A shell script, which combines make and colormake.pl

Installation
------------

```
    mkdir ~/bin
    cp colormake.pl colormake ~/bin/
    echo PATH=~/bin:$PATH >> ~/.bashrc
    source ~/.bashrc
```

Usage
-----

Type `colormake` whenever you'd ordinarily type `make`.

Author
------

Medicine Yeh

Relative Author
Bjarni R. Einarsson, <http://bre.klaki.net/>.


