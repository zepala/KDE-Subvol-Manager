# KDE-Subvol-Manager

This is a complete rewrite of BTRFS Subvolume Manager 2018 v0.3 By Stuart K. Smith <stuartksmith@gmail.com>

Removed all dependencies to non kde apps. Rewrited all functions on a unique file

Added two files for the konfiguration of PolicyKit.

# Installation :

Copy subvol_manager.desktop file and subvol_manager-scripts directory to $HOME/.local/share/kservices5/ServiceMenus/

# Configuration :

If you don't want to be asked for password every time you use the menu, copy 'org.local.pkexec.btrfs.policy' to /usr/share/polkit-1/actions/, and
copy 'btrfs.pkla' to /etc/polkit-1/localauthority/50-local.d/
