
Debian
====================
This directory contains files used to package nodeod/nodeo-qt
for Debian-based Linux systems. If you compile nodeod/nodeo-qt yourself, there are some useful files here.

## nodeo: URI support ##


nodeo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nodeo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nodeoqt binary to `/usr/bin`
and the `../../share/pixmaps/nodeo128.png` to `/usr/share/pixmaps`

nodeo-qt.protocol (KDE)

