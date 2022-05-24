
Debian
====================
This directory contains files used to package bdcashprotocold/bdcashprotocol-qt
for Debian-based Linux systems. If you compile bdcashprotocold/bdcashprotocol-qt yourself, there are some useful files here.

## bdcashprotocol: URI support ##


bdcashprotocol-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bdcashprotocol-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bdcashprotocolqt binary to `/usr/bin`
and the `../../share/pixmaps/bdcashprotocol128.png` to `/usr/share/pixmaps`

bdcashprotocol-qt.protocol (KDE)

