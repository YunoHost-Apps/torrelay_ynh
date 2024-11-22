<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Tor relay YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/torrelay.svg)](https://ci-apps.yunohost.org/ci/apps/torrelay/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/torrelay.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/torrelay.maintain.svg)

[![Instalatu Tor relay YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=torrelay)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Tor relay YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

The Tor network relies on volunteers to donate bandwidth. The more people who run relays, the better the Tor network will be. The current Tor network is quite small compared to the number of people who need to use Tor, which means we need more dedicated volunteers like you to run relays.

**Paketatutako bertsioa:** 0.4.8.12~ynh1

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.torproject.org/>
- Administratzaileen dokumentazio ofiziala: <https://community.torproject.org/relay/setup/bridge/debian-ubuntu/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/torproject/tor>
- YunoHost Denda: <https://apps.yunohost.org/app/torrelay>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/torrelay_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
edo
sudo yunohost app upgrade torrelay -u https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
