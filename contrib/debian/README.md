
Debian
====================
This directory contains files used to package eliqad/eliqa-qt
for Debian-based Linux systems. If you compile eliqad/eliqa-qt yourself, there are some useful files here.

## eliqa: URI support ##


eliqa-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eliqa-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eliqaqt binary to `/usr/bin`
and the `../../share/pixmaps/eliqa128.png` to `/usr/share/pixmaps`

eliqa-qt.protocol (KDE)

