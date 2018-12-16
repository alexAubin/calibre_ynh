
# Calibre-web for YunoHost

[![Install calibreweb with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=calibreweb)

> *This package allow you to install calibreweb quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
This is an implementation of [Calibre-web](https://github.com/janeczku/calibre-web) for Yunohost.

Calibre-Web is a web app providing a clean interface for browsing, reading and downloading eBooks using an existing [Calibre](https://calibre-ebook.com) database.

*This software is a fork of [library](https://github.com/mutschler/calibreserver) and licensed under the GPL v3 License.*

**Shipped version:** To be 1.0, let's say 0.9 :)

## Screenshots

![screenshot](https://raw.githubusercontent.com/janeczku/docker-calibre-web/master/screenshot.png)

## Limitations

* No LDAP support
* access to library to be done manually after install if Calibre library was already existing, for example :
```
chown -R calibreweb: path/to/library
or
chmod o+rw path/to/library
``` 

## Links

 * Report a bug: https://github.com/YunoHost-Apps/calibreweb_ynh/issues
 * App website: https://github.com/janeczku/calibre-web
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/calibreweb_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/Krakinou/calibreweb_ynh/tree/Testing --debug
or
sudo yunohost app upgrade calibreweb -u https://github.com/Krakinou/calibreweb_ynh/tree/Testing --debug
```
