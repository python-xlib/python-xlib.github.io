# python-xlib.github.io

GitHub Pages site for python-xlib

## Generating documentation

Install `texi2html` and `tetext` packages first. Afterwards:

    git clone https://github.com/python-xlib/python-xlib.github.io
    git clone https://github.com/python-xlib/python-xlib
    pushd python-xlib/doc && make && popd
    cp python-xlib/doc/html/*.html python-xlib.github.io
