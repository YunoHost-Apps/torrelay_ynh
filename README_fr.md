# Tor relay pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/torrelay.svg)](https://dash.yunohost.org/appci/app/torrelay) ![](https://ci-apps.yunohost.org/ci/badges/torrelay.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/torrelay.maintain.svg)  
[![Installer Tor relay avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=torrelay)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Tor relay rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

The Tor network relies on volunteers to donate bandwidth. The more people who run relays, the better the Tor network will be. The current Tor network is quite small compared to the number of people who need to use Tor, which means we need more dedicated volunteers like you to run relays.

**Version incluse :** 0.4.6.10~ynh1



## Documentations et ressources

* Site officiel de l'app : https://www.torproject.org/
* Documentation officielle de l'admin : https://community.torproject.org/relay/setup/bridge/debian-ubuntu/
* Dépôt de code officiel de l'app : https://github.com/torproject/tor
* Documentation YunoHost pour cette app : https://yunohost.org/app_torrelay
* Signaler un bug : https://github.com/YunoHost-Apps/torrelay_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
ou
sudo yunohost app upgrade torrelay -u https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps