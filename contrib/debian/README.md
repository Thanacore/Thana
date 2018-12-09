
Debian
====================
This directory contains files used to package thanad/thana-qt
for Debian-based Linux systems. If you compile thanad/thana-qt yourself, there are some useful files here.

## thana: URI support ##


thana-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install thana-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your thanaqt binary to `/usr/bin`
and the `../../share/pixmaps/thana128.png` to `/usr/share/pixmaps`

thana-qt.protocol (KDE)

