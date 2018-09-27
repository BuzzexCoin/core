
Debian
====================
This directory contains files used to package buzzexcoind/buzzexcoin-qt
for Debian-based Linux systems. If you compile buzzexcoind/buzzexcoin-qt yourself, there are some useful files here.

## buzzexcoin: URI support ##


buzzexcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install buzzexcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your buzzexcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/buzzexcoin128.png` to `/usr/share/pixmaps`

buzzexcoin-qt.protocol (KDE)

