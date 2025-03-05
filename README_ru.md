<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Actual для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/actual)](https://ci-apps.yunohost.org/ci/apps/actual/)
![Состояние работы](https://apps.yunohost.org/badge/state/actual)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/actual)

[![Установите Actual с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=actual)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Actual быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Actual is a local-first personal finance tool. It is 100% free and open-source, written in NodeJS, it has a synchronization element so that all your changes can move between devices without any heavy lifting.

**Поставляемая версия:** 25.3.1~ynh1

## Снимки экрана

![Снимок экрана Actual](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальная документация администратора: <https://actualbudget.github.io/docs/>
- Репозиторий кода главной ветки приложения: <https://github.com/actualbudget/actual-server>
- Магазин YunoHost: <https://apps.yunohost.org/app/actual>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/actual_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/actual_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/actual_ynh/tree/testing --debug
или
sudo yunohost app upgrade actual -u https://github.com/YunoHost-Apps/actual_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
