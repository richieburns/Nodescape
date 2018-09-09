
Debian
====================
This directory contains files used to package nodescaped/nodescape-qt
for Debian-based Linux systems. If you compile nodescaped/nodescape-qt yourself, there are some useful files here.

## nodescape: URI support ##


nodescape-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nodescape-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nodescape-qt binary to `/usr/bin`
and the `../../share/pixmaps/nodescape128.png` to `/usr/share/pixmaps`

nodescape-qt.protocol (KDE)

