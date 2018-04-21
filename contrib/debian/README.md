
Debian
====================
This directory contains files used to package dextrod/dextro-qt
for Debian-based Linux systems. If you compile dextrod/dextro-qt yourself, there are some useful files here.

## dextro: URI support ##


dextro-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dextro-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dextroqt binary to `/usr/bin`
and the `../../share/pixmaps/dextro128.png` to `/usr/share/pixmaps`

dextro-qt.protocol (KDE)

