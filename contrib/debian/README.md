
Debian
====================
This directory contains files used to package lumocashd/lumocash-qt
for Debian-based Linux systems. If you compile lumocashd/lumocash-qt yourself, there are some useful files here.

## lumocash: URI support ##


lumocash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lumocash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lumocash-qt binary to `/usr/bin`
and the `../../share/pixmaps/lumocash128.png` to `/usr/share/pixmaps`

lumocash-qt.protocol (KDE)

