
Debian
====================
This directory contains files used to package cpacoind/cpacoin-qt
for Debian-based Linux systems. If you compile cpacoind/cpacoin-qt yourself, there are some useful files here.

## cpacoin: URI support ##


cpacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cpacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cpacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/cpacoin128.png` to `/usr/share/pixmaps`

cpacoin-qt.protocol (KDE)

