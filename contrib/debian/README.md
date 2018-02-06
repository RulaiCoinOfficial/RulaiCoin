
Debian
====================
This directory contains files used to package rulaicoind/rulaicoin-qt
for Debian-based Linux systems. If you compile rulaicoind/rulaicoin-qt yourself, there are some useful files here.

## rulaicoin: URI support ##


rulaicoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rulaicoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rulaicoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/rulaicoin128.png` to `/usr/share/pixmaps`

rulaicoin-qt.protocol (KDE)

