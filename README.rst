=========
i3-castle
=========

i3 window manager configuration files.

------------
Requirements
------------

- ``urxvt`` as a terminal emulator
- ``i3status`` (ships with ``i3``) for the status bar
- ``unclutter`` to hide the mouse after a period of inactivity
- ``gnome-settings-daemon``
- ``feh`` for wallpapers
- ``guake`` to have a terminal always at hand
- ``compton`` as a composite manager to render ``guake`` transparent
- ``amixer`` and ``pulse`` for audio control

-----------
Keybindings
-----------

The keybindings rely heavily on modes.
The default mode only has one keybinding ``Alt-R`` configured to enter the main mode.
You can always go back to the default mode with ``ESC`` or ``SPC``.

I chose this setup because I mostly have to press one key at a time.
``SPC`` is always in reach, so quitting is really fast and becomes
part of the muscle memory really fast.

``Backspace`` will always go to the parent mode.

For moving ``i``, ``j``, ``k``, ``l`` is used in multiple contexts.

-------
Credits
-------

This config is heavily inspired by `syl20bnr's config <https://github.com/syl20bnr/i3ci>`_.
It helped me a lot putting this together.
