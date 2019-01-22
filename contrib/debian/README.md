
Debian
====================
This directory contains files used to package gentariumd/gentarium-qt
for Debian-based Linux systems. If you compile gentariumd/gentarium-qt yourself, there are some useful files here.

## gentarium: URI support ##


gentarium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gentarium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gentariumqt binary to `/usr/bin`
and the `../../share/pixmaps/gentarium128.png` to `/usr/share/pixmaps`

gentarium-qt.protocol (KDE)

