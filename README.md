# Game-Servers

An archive of useful systemd services and other config files for the various game servers that I maintain.

* [Minecraft Systemd](minecraft/minecraft@.service) - A simple systemd service for running several minecraft servers at once using one service file.
* [Terraria Systemd](terraria/terraria.service) - A simple systemd service for running terraria with a screen session and safe shutdown.

## Installation

Install `screen` with:

```
$ sudo apt install screen
```

Install the systemd scripts by copying them to `/etc/systemd/system/`.
Manage them just like any other systemd service.
