
Debian
====================
This directory contains files used to package grootd/groot-qt
for Debian-based Linux systems. If you compile grootd/groot-qt yourself, there are some useful files here.

## groot: URI support ##


groot-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install groot-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your groot-qt binary to `/usr/bin`
and the `../../share/pixmaps/groot128.png` to `/usr/share/pixmaps`

groot-qt.protocol (KDE)

