# Common commands

```
apt-get update
```

By using the sudo apt-get update command, the package lists are re-read and updated. These are stored in the directory `/etc/apt/sources.list` and are different depending on the version and have different variables at the end.

```
apt-get upgrade
```

The sudo apt-get upgrade command performs the actual "update", in this case referred to as upgrading the system. Installed here are all new versions of a package, if updates are available. The packages are installed on top of the packages already present on the system. None are exchanged and replaced with new ones.
