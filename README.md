# CouchPotato for YunoHost

[![Integration level](https://dash.yunohost.org/integration/couchpotato.svg)](https://dash.yunohost.org/appci/app/couchpotato) ![](https://ci-apps.yunohost.org/ci/badges/couchpotato.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/couchpotato.maintain.svg)  
[![Install CouchPotato with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=couchpotato)

> *This package allows you to install CouchPotato quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Download movies automatically, easily and in the best quality as soon as they are available.

- Integrates automatically with [transmission_ynh](https://github.com/YunoHost-Apps/transmission_ynh) (or tries to...),
- Integrates [YunoHost multimedia](https://github.com/YunoHost-Apps/yunohost.multimedia) folder structure

**Shipped version:** 3.0.1

## YunoHost specific features

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/couchpotato%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/couchpotato/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/couchpotato%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/couchpotato/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/couchpotato_ynh/issues
 * App website: https://couchpota.to
 * Upstream app repository: https://github.com/CouchPotato/CouchPotatoServer
 * YunoHost website: https://yunohost.org/

#### Special Thanks to the Yunohost Community:
[Snipees](https://github.com/Snipees)
[anaqreon](https://github.com/anaqreon), 
[aymhce](https://github.com/aymhce), 
[beudbeud](https://github.com/abeudin), 
[Chao-Man](https://github.com/Chao-Man), 
[chtixof](https://github.com/chtixof), 
[CotzaDev](https://github.com/CotzaDev), 
[courgette](https://github.com/courgette), 
[Jérôme](https://github.com/jeromelebleu), 
[JocelynD](https://github.com/JocelynDelalande), 
[Ju](https://github.com/julienmalik), 
[Le Kload](https://github.com/Kloadut), 
[lunarok](https://github.com/lunarok), 
[maniackcrudelis](https://github.com/maniackcrudelis), 
[Matlink](https://github.com/matlink), 
[Moul](https://github.com/M5oul), 
[polytan02](https://github.com/polytan02), 
[scith](https://github.com/scith), 
[tifred](https://github.com/drfred1981), 
... :dizzy:

---

Developer info
----------------

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/couchpotato_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/couchpotato_ynh/tree/testing --debug
or
sudo yunohost app upgrade couchpotato -u https://github.com/YunoHost-Apps/couchpotato_ynh/tree/testing --debug
```
