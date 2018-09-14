
Debian
====================
This directory contains files used to package trepcod/trepco-qt
for Debian-based Linux systems. If you compile trepcod/trepco-qt yourself, there are some useful files here.

## trepco: URI support ##


trepco-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install trepco-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your trepcoqt binary to `/usr/bin`
and the `../../share/pixmaps/trepco128.png` to `/usr/share/pixmaps`

trepco-qt.protocol (KDE)

