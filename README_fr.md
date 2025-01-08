<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Actual pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/actual)](https://ci-apps.yunohost.org/ci/apps/actual/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/actual)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/actual)

[![Installer Actual avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=actual)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Actual rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Actual est un outil de finances personnelles local. Il est 100% gratuit et open-source, écrit en NodeJS, il dispose d'un élément de synchronisation afin que toutes vos modifications puissent se déplacer entre les appareils sans aucune lourde charge.

**Version incluse :** 25.1.0~ynh1

## Captures d’écran

![Capture d’écran de Actual](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Documentation officielle de l’admin : <https://actualbudget.github.io/docs/>
- Dépôt de code officiel de l’app : <https://github.com/actualbudget/actual-server>
- YunoHost Store : <https://apps.yunohost.org/app/actual>
- Signaler un bug : <https://github.com/YunoHost-Apps/actual_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/actual_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/actual_ynh/tree/testing --debug
ou
sudo yunohost app upgrade actual -u https://github.com/YunoHost-Apps/actual_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
