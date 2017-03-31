# PostgreSQL

## Install

To install run:

```
$ brew update
$ brew install postgresql
```

Usage

To have launchd start postgresql now and restart at login:

```
$ brew services start postgresql
```









Or, if you don't want/need a background service you can just run:

$ pg\_ctl -D /usr/local/var/postgres start

