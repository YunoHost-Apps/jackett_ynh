<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Jackett for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/jackett)](https://ci-apps.yunohost.org/ci/apps/jackett/)
![Working status](https://apps.yunohost.org/badge/state/jackett)
![Maintenance status](https://apps.yunohost.org/badge/maintained/jackett)

[![Install Jackett with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jackett)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Jackett quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Jackett works as a proxy server: it translates queries from apps (Sonarr, Radarr, SickRage, CouchPotato, Mylar3, Lidarr, DuckieTV, qBittorrent, Nefarious etc.) into tracker-site-specific http queries, parses the html or json response, and then sends results back to the requesting software. This allows for getting recent uploads (like RSS) and performing searches. Jackett is a single repository of maintained indexer scraping & translation logic - removing the burden from other apps.


**Shipped version:** 0.22.1695~ynh1

## Screenshots

![Screenshot of Jackett](./doc/screenshots/demo.png)

## Documentation and resources

- Upstream app code repository: <https://github.com/Jackett/Jackett>
- YunoHost Store: <https://apps.yunohost.org/app/jackett>
- Report a bug: <https://github.com/YunoHost-Apps/jackett_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/jackett_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/jackett_ynh/tree/testing --debug
or
sudo yunohost app upgrade jackett -u https://github.com/YunoHost-Apps/jackett_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
