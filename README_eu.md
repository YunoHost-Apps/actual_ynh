<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Actual YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/actual.svg)](https://dash.yunohost.org/appci/app/actual) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/actual.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/actual.maintain.svg)

[![Instalatu Actual YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=actual)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Actual YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Actual is a local-first personal finance tool. It is 100% free and open-source, written in NodeJS, it has a synchronization element so that all your changes can move between devices without any heavy lifting.

**Paketatutako bertsioa:** 24.6.0~ynh1

## Pantaila-argazkiak

![Actual(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://actualbudget.github.io/docs/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/actualbudget/actual-server>
- YunoHost Denda: <https://apps.yunohost.org/app/actual>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/actual_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/actual_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/actual_ynh/tree/testing --debug
edo
sudo yunohost app upgrade actual -u https://github.com/YunoHost-Apps/actual_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
