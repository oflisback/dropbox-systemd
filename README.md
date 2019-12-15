# Dropbox with systemd on Arch

This is a systemd service file to start up dropbox for a user on boot.

## Prerequisites

Arch package [dropbox](https://wiki.archlinux.org/index.php/Dropbox) has been installed.

## Installation

* Place the dropbox@.service file into /etc/systemd/system
* Reload the daemons: systemctl daemon-reload
* Enable the service for users: systemctl enable dropbox@username
* Start service: systemctl start dropbox@username
