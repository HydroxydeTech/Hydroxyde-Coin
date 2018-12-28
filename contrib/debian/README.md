
Debian
====================
This directory contains files used to package hydroxyded/hydroxyde-qt
for Debian-based Linux systems. If you compile hydroxyded/hydroxyde-qt yourself, there are some useful files here.

## hydroxyde: URI support ##


hydroxyde-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hydroxyde-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hydroxydeqt binary to `/usr/bin`
and the `../../share/pixmaps/hydroxyde128.png` to `/usr/share/pixmaps`

hydroxyde-qt.protocol (KDE)
