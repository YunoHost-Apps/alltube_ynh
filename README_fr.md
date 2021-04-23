# AllTube pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/alltube.svg)](https://dash.yunohost.org/appci/app/alltube) ![](https://ci-apps.yunohost.org/ci/badges/alltube.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/alltube.maintain.svg)  
[![Installer AllTube avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=alltube)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer AllTube rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
AllTube est une IHM web pour Youtube-dl.

**Version incluse:** 3.0.0

## Captures d'écran

![Captures d'écran](https://github.com/Rudloff/alltube/raw/master/img/screenshot.png "alltube IHM")

## Démo

* [Démo officielle](https://alltubedownload.net/)

## Configuration

Pour configurer AllTube : éditez le fichier `config.yml` via SSH.

## Documentation

 * Pas de documentation officelle, une simple [FAQ](https://github.com/Rudloff/alltube/blob/master/resources/FAQ.md)

#### Support multi-utilisateur

Pas de compte utilisateur dans l'application

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/alltube%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/alltube/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/alltube%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/alltube/)

## Liens

 * Signaler un bug: https://github.com/YunoHost-Apps/alltube_ynh/issues
 * Site de l'application: https://alltubedownload.net/
 * Sources de l'application: https://github.com/Rudloff/alltube
 * Site web YunoHost: https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/alltube_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/alltube_ynh/tree/testing --debug
ou
sudo yunohost app upgrade alltube -u https://github.com/YunoHost-Apps/alltube_ynh/tree/testing --debug
```
