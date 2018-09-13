
Debian
====================
This directory contains files used to package egamescoind/egamescoin-qt
for Debian-based Linux systems. If you compile egamescoind/egamescoin-qt yourself, there are some useful files here.

## egamescoin: URI support ##


egamescoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install egamescoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your egamescoinqt binary to `/usr/bin`
and the `../../share/pixmaps/egamescoin128.png` to `/usr/share/pixmaps`

egamescoin-qt.protocol (KDE)

