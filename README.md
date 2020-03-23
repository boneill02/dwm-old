# sweg's build of dwm

Here's my build of dwm.

## FAQ

Check the man pages.

## Please install `libxft-bgra`!

This build of dwm does not block color emoji in the status/info bar,
so you must install
[libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from
the AUR, which fixes a libxft color emoji rendering problem, otherwise
dwm will crash upon trying to render one. Hopefully this fix will be
in all libxft soon enough.
