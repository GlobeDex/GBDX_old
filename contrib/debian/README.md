
Debian
====================
This directory contains files used to package globedexd/globedex-qt
for Debian-based Linux systems. If you compile globedexd/globedex-qt yourself, there are some useful files here.

## globedex: URI support ##


globedex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install globedex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your globedex-qt binary to `/usr/bin`
and the `../../share/pixmaps/globedex128.png` to `/usr/share/pixmaps`

globedex-qt.protocol (KDE)

