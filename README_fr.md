# App exemple pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/alltube.svg)](https://dash.yunohost.org/appci/app/alltube)
[![Install alltube with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=alltube)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer alltube rapidement et simplement sur un serveur Yunohost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble
Alltube est une IHM web pour Youtube-dl.


**Version incluse:** 2.3.0

## Captures d'écran

![Captures d'écran](https://github.com/Rudloff/alltube/raw/master/img/screenshot.png "alltube IHM")

## Démo

* [Démo officielle](https://alltubedownload.net/)


## Configuration

Pour configurer Alltube :
> Edit config.yml file via SSH.

## Documentation

 * Pas de documentation officelle, une simple [FAQ](https://github.com/Rudloff/alltube/blob/master/resources/FAQ.md)

#### Support multi-utilisateurs

Pas de compte utilisateur dans l'application

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/alltube%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/alltube/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/alltube%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/alltube/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/alltube%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/alltube/)

## Links

 * Signaler un bug: https://github.com/YunoHost-Apps/alltube_ynh/issues
 * Site de l'application: https://alltubedownload.net/
 * Sources de l'application: https://github.com/Rudloff/alltube
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/alltube_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/alltube_ynh/tree/testing --debug
ou
sudo yunohost app upgrade alltube -u https://github.com/YunoHost-Apps/alltube_ynh/tree/testing --debug
```
