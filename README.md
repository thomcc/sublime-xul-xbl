# Sublime XUL / XBL highlighting

Adds a "XUL or XBL" syntax option.

Note: This is unlikely to be useful unless you work on Firefox.

## Installation

At the moment, clone this repo into your Packages directory. Eventually you'll be able to use package control, hopefully.

Set `*.xml`, `*.xul`, and `*.dtd` files to open with this syntax populate the symbol list and index, so that "Go To Symbol in Package" (`Cmd+Shift+R` or `Ctrl+Shift+R`) can jump to XBL `<method>`s and `<!ENTITY`s the localization dtd files.

## Features

- Improved syntax highlighting for files containing XBL and XUL.
- XBL methods are available in the symbol list and index, e.g. Go To Symbol works for them (Requires that this be the default syntax for the files they're present in).
- `<!ENTITY` declarations are available in the symbol list in index (must be default syntax for their files, as above).

## Screenshots

- XBL support, comparison with HTML and XML syntaxes:

![xul-xbl-vs-xml-vs-html](https://raw.githubusercontent.com/thomcc/sublime-xul-xbl/216e34ea65cb9834664eb090bae5d3f218e11fa0/Screenshots/XBL-Compare.png)

- Mozilla preprocessor support:

![xul-preproc-example](https://raw.githubusercontent.com/thomcc/sublime-xul-xbl/216e34ea65cb9834664eb090bae5d3f218e11fa0/Screenshots/XUL-Preproc.png)

- Various other XUL support features:

![xul-basic](https://raw.githubusercontent.com/thomcc/sublime-xul-xbl/216e34ea65cb9834664eb090bae5d3f218e11fa0/Screenshots/XUL-Basic.png)
