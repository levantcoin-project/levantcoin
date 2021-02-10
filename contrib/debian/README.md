
Debian
====================
This directory contains files used to package levantcoind/levantcoin-qt
for Debian-based Linux systems. If you compile levantcoind/levantcoin-qt yourself, there are some useful files here.

## levantcoin: URI support ##


levantcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install levantcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your levantcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/levantcoin128.png` to `/usr/share/pixmaps`

levantcoin-qt.protocol (KDE)

