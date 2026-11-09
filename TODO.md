# TODO

In no particular order:

- rename
- remove built-in xwallpaper command call
- change minimize/unmap behavior to typical minimize behavior
- fully stack windows in monocle layout (remove `space-between-monocle` option)
- no borders on fullscreen (remove fullscreen-border option)

## Unnecessary

- rewrite in V

## openmamba-based linux distribution

Comes with this window manager.

- display manager: undecided, probably lxdm because it is officially maintained by openmamba already.
- launcher: undecided, probably custom.
- notifications: undecided, probably custom.
- bar: [Qelxiros/lazybar](https://github.com/Qelxiros/lazybar), eventually custom.
- clipboard manager: undecided.
- screen locker: undecided.
- terminal: [contour-terminal/contour](https://github.com/contour-terminal/contour).
- file manager: [elio-fm/elio](https://github.com/elio-fm/elio).
- secrets: [grimsteel/pass-secret-service](https://github.com/grimsteel/pass-secret-service) and [grimsteel/pass-nm-agent](https://github.com/grimsteel/pass-nm-agent)

All other stuff can be installed by users, don't even include a web browser, anyone can `dnf install firefox`.
