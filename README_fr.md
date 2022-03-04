# AllTube pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/alltube.svg)](https://dash.yunohost.org/appci/app/alltube) ![](https://ci-apps.yunohost.org/ci/badges/alltube.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/alltube.maintain.svg)  
[![Installer AllTube avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=alltube)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer AllTube rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Interface Web pour Youtube-dl

**Version incluse :** 3.0.2~ynh1

**Démo :** https://alltubedownload.net/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## Configuration

Pour configurer AllTube : éditez le fichier `/var/www/alltube/config/config.yml` via SSH.

## Documentations et ressources

* Site officiel de l'app : https://alltubedownload.net/
* Documentation officielle de l'admin : https://github.com/Rudloff/alltube/blob/master/resources/FAQ.md
* Dépôt de code officiel de l'app : https://github.com/Rudloff/alltube
* Documentation YunoHost pour cette app : https://yunohost.org/app_alltube
* Signaler un bug : https://github.com/YunoHost-Apps/alltube_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/alltube_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/alltube_ynh/tree/testing --debug
ou
sudo yunohost app upgrade alltube -u https://github.com/YunoHost-Apps/alltube_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps