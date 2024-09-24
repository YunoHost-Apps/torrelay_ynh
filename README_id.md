<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Tor relay untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/torrelay.svg)](https://ci-apps.yunohost.org/ci/apps/torrelay/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/torrelay.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/torrelay.maintain.svg)

[![Pasang Tor relay dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=torrelay)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Tor relay secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

The Tor network relies on volunteers to donate bandwidth. The more people who run relays, the better the Tor network will be. The current Tor network is quite small compared to the number of people who need to use Tor, which means we need more dedicated volunteers like you to run relays.

**Versi terkirim:** 0.4.8.10~ynh2
## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.torproject.org/>
- Dokumentasi admin resmi: <https://community.torproject.org/relay/setup/bridge/debian-ubuntu/>
- Depot kode aplikasi hulu: <https://github.com/torproject/tor>
- Gudang YunoHost: <https://apps.yunohost.org/app/torrelay>
- Laporkan bug: <https://github.com/YunoHost-Apps/torrelay_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
atau
sudo yunohost app upgrade torrelay -u https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
