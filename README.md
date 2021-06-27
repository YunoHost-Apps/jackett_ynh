<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Jackett for YunoHost

[![Integration level](https://dash.yunohost.org/integration/jackett.svg)](https://dash.yunohost.org/appci/app/jackett) ![](https://ci-apps.yunohost.org/ci/badges/jackett.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/jackett.maintain.svg)  
[![Install Jackett with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jackett)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Jackett quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

It provides API support for your favorite torrent trackers.

**Shipped version:** 0.18.98~ynh1

**Demo:** https://github.com/Jackett/Jackett

## Screenshots

![](./doc/screenshots/demo.png)

## Disclaimers / important information

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * No LDAP Support
## Documentation and resources

* Official app website: https://github.com/Jackett/Jackett
* Official user documentation: https://yunohost.org/apps
* Official admin documentation: https://yunohost.org/packaging_apps
* Upstream app code repository: https://github.com/Jackett/Jackett
* YunoHost documentation for this app: https://yunohost.org/app_jackett
* Report a bug: https://github.com/YunoHost-Apps/jackett_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/jackett_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/jackett_ynh/tree/testing --debug
or
sudo yunohost app upgrade jackett -u https://github.com/YunoHost-Apps/jackett_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps