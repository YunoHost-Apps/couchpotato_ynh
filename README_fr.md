# CouchPotato pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/couchpotato.svg)](https://dash.yunohost.org/appci/app/couchpotato) ![](https://ci-apps.yunohost.org/ci/badges/couchpotato.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/couchpotato.maintain.svg)  
[![Installer CouchPotato avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=couchpotato)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer CouchPotato rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Téléchargement automatisé de film

**Version incluse :** 3.0.1~ynh3



## Avertissements / informations importantes

* Other infos that people should be aware of, such as:
    * Integrates automatically with [transmission_ynh](https://github.com/YunoHost-Apps/transmission_ynh) (or tries to...),
    * Integrates [YunoHost multimedia](https://github.com/YunoHost-Apps/yunohost.multimedia) folder structure

## Documentations et ressources

* Site officiel de l'app : https://couchpota.to
* Dépôt de code officiel de l'app : https://github.com/CouchPotato/CouchPotatoServer
* Documentation YunoHost pour cette app : https://yunohost.org/app_couchpotato
* Signaler un bug : https://github.com/YunoHost-Apps/couchpotato_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/couchpotato_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/couchpotato_ynh/tree/testing --debug
ou
sudo yunohost app upgrade couchpotato -u https://github.com/YunoHost-Apps/couchpotato_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps