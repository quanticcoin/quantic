
Debian
====================
This directory contains files used to package quanticd/quantic-qt
for Debian-based Linux systems. If you compile quanticd/quantic-qt yourself, there are some useful files here.

## quantic: URI support ##


quantic-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install quantic-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your quanticqt binary to `/usr/bin`
and the `../../share/pixmaps/quantic128.png` to `/usr/share/pixmaps`

quantic-qt.protocol (KDE)

