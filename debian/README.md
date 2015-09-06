
Debian
====================
This directory contains files used to package monacoind/monacoin-qt
for Debian-based Linux systems. If you compile monacoind/monacoin-qt yourself, there are some useful files here.

## monacoin: URI support ##


monacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install monacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your monacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/monacoin128.png` to `/usr/share/pixmaps`

monacoin-qt.protocol (KDE)

