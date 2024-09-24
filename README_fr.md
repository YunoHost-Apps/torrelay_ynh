<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Tor relay pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/torrelay.svg)](https://ci-apps.yunohost.org/ci/apps/torrelay/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/torrelay.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/torrelay.maintain.svg)

[![Installer Tor relay avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=torrelay)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Tor relay rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Le réseau Tor dépend des bénévoles qui donnent de la bande passante. Plus il y aura de personnes qui géreront les relais, meilleur sera le réseau Tor. Le réseau Tor actuel est assez petit par rapport au nombre de personnes qui ont besoin d'utiliser Tor, ce qui signifie que nous avons besoin de plus de bénévoles dévoués comme vous pour gérer les relais.

**Version incluse :** 0.4.8.12~ynh1
## Documentations et ressources

- Site officiel de l’app : <https://www.torproject.org/>
- Documentation officielle de l’admin : <https://community.torproject.org/relay/setup/bridge/debian-ubuntu/>
- Dépôt de code officiel de l’app : <https://github.com/torproject/tor>
- YunoHost Store : <https://apps.yunohost.org/app/torrelay>
- Signaler un bug : <https://github.com/YunoHost-Apps/torrelay_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
ou
sudo yunohost app upgrade torrelay -u https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
