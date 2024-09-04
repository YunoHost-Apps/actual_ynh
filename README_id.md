<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Actual untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/actual.svg)](https://ci-apps.yunohost.org/ci/apps/actual/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/actual.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/actual.maintain.svg)

[![Pasang Actual dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=actual)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Actual secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Actual is a local-first personal finance tool. It is 100% free and open-source, written in NodeJS, it has a synchronization element so that all your changes can move between devices without any heavy lifting.

**Versi terkirim:** 24.9.0~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Actual](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Dokumentasi admin resmi: <https://actualbudget.github.io/docs/>
- Depot kode aplikasi hulu: <https://github.com/actualbudget/actual-server>
- Gudang YunoHost: <https://apps.yunohost.org/app/actual>
- Laporkan bug: <https://github.com/YunoHost-Apps/actual_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/actual_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/actual_ynh/tree/testing --debug
atau
sudo yunohost app upgrade actual -u https://github.com/YunoHost-Apps/actual_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
