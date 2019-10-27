# alltube app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/alltube.svg)](https://dash.yunohost.org/appci/app/alltube)
[![Install alltube with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=alltube)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install alltube quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
alltube is a HTML GUI for Youtube-dl.

**Shipped version:** 2.0.5

## Screenshots

![Screenshot](https://github.com/Rudloff/alltube/raw/master/img/screenshot.png "alltube GUI screenshot")

## Demo

* [Official demo](https://alltubedownload.net/)

## Configuration

How to configure this app:
> Edit config.yml file via SSH.

## Documentation

 * No documentation, only a [FAQ](https://github.com/Rudloff/alltube/blob/master/resources/FAQ.md)

#### Multi-users support

There is no user account in the app.

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/alltube%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/alltube/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/alltube%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/alltube/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/alltube%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/alltube/)


## Links

 * Report a bug: https://github.com/YunoHost-Apps/alltube_ynh/issues
 * App website: https://alltubedownload.net/
 * App sources: https://github.com/Rudloff/alltube
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/alltube_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/alltube_ynh/tree/testing --debug
or
sudo yunohost app upgrade alltube -u https://github.com/YunoHost-Apps/alltube_ynh/tree/testing --debug
```
