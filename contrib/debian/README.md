
Debian
====================
This directory contains files used to package wacd/wac-qt
for Debian-based Linux systems. If you compile wacd/wac-qt yourself, there are some useful files here.

## wac: URI support ##


wac-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wac-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wacqt binary to `/usr/bin`
and the `../../share/pixmaps/wac128.png` to `/usr/share/pixmaps`

wac-qt.protocol (KDE)

