
Debian
====================
This directory contains files used to package dzcoind/dzcoin-qt
for Debian-based Linux systems. If you compile dzcoind/dzcoin-qt yourself, there are some useful files here.

## dzcoin: URI support ##


dzcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dzcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dzcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/dzcoin128.png` to `/usr/share/pixmaps`

dzcoin-qt.protocol (KDE)

