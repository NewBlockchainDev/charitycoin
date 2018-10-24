
Debian
====================
This directory contains files used to package charitycoind/charitycoin-qt
for Debian-based Linux systems. If you compile charitycoind/charitycoin-qt yourself, there are some useful files here.

## charitycoin: URI support ##


charitycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install charitycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your charitycoinqt binary to `/usr/bin`
and the `../../share/pixmaps/charitycoin128.png` to `/usr/share/pixmaps`

charitycoin-qt.protocol (KDE)

