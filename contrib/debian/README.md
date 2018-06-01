
Debian
====================
This directory contains files used to package BSGd/BSG-qt
for Debian-based Linux systems. If you compile BSGd/BSG-qt yourself, there are some useful files here.

## BSG: URI support ##


BSG-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install BSG-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your BSGqt binary to `/usr/bin`
and the `../../share/pixmaps/BSG128.png` to `/usr/share/pixmaps`

BSG-qt.protocol (KDE)

