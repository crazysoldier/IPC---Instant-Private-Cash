
Debian
====================
This directory contains files used to package ipcashd/ipcash-qt
for Debian-based Linux systems. If you compile ipcashd/ipcash-qt yourself, there are some useful files here.

## ipcash: URI support ##


ipcash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ipcash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ipcashqt binary to `/usr/bin`
and the `../../share/pixmaps/ipcash128.png` to `/usr/share/pixmaps`

ipcash-qt.protocol (KDE)

