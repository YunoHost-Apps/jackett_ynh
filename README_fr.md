# Jackett pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/jackett.svg)](https://dash.yunohost.org/appci/app/jackett) ![](https://ci-apps.yunohost.org/ci/badges/jackett.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/jackett.maintain.svg)  
[![Installer Jackett avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jackett)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Jackett rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

API pour vos trackers torrent préférés

**Version incluse :** 0.20.53~ynh1

**Démo :** https://github.com/Jackett/Jackett

## Captures d'écran

![](./doc/screenshots/demo.png)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * No LDAP Support
## Documentations et ressources

* Site officiel de l'app : https://github.com/Jackett/Jackett
* Dépôt de code officiel de l'app : https://github.com/Jackett/Jackett
* Documentation YunoHost pour cette app : https://yunohost.org/app_jackett
* Signaler un bug : https://github.com/YunoHost-Apps/jackett_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/jackett_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/jackett_ynh/tree/testing --debug
ou
sudo yunohost app upgrade jackett -u https://github.com/YunoHost-Apps/jackett_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps