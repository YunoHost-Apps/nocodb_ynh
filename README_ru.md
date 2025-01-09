<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# NocoDB для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/nocodb)](https://ci-apps.yunohost.org/ci/apps/nocodb/)
![Состояние работы](https://apps.yunohost.org/badge/state/nocodb)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/nocodb)

[![Установите NocoDB с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить NocoDB быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

NocoDB is an open source NoCode platform that turns any database into a smart spreadsheet, alternative to Airtable.

* Connect to new/existing SQL database and turn them into spreadsheet
* Create grid view, gallery view, kanban view and calendar view on top your data
* Search, sort, filter columns and rows with ultra ease
* Invite your team with fine grained Access Control
* Share views publicly and also with password protection
* Provides REST & GraphQL APIs with Swagger & GraphiQL GUI


**Поставляемая версия:** 0.260.1~ynh1

**Демо-версия:** <https://www.nocodb.com/demos>

## Снимки экрана

![Снимок экрана NocoDB](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.nocodb.com>
- Репозиторий кода главной ветки приложения: <https://github.com/nocodb/nocodb>
- Магазин YunoHost: <https://apps.yunohost.org/app/nocodb>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/nocodb_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
или
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
