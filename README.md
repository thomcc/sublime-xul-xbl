# Sublime XUL / XBL highlighting

This is unlikely to be useful unless you work on Firefox.

Adds a "XUL or XBL" syntax option. I set all `*.xml` and `*.xul` files to open with this on my work machine, but I could understand only wanting to do it for `*.xul`.

It sets the scope of XBL methods/etc (e.g. `<method name="whatever">` and such) correctly so that they should show up in the symbol index (e.g. goto symbol, Cmd+Shift+R or whatever you have it bound to). This may only work if you reconfigure xml files to open with this syntax.

# Installation

At the moment, clone this repo into your Packages directory. Eventually you'll be able to use package control.
