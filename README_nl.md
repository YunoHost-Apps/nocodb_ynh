<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# NocoDB voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/nocodb)](https://ci-apps.yunohost.org/ci/apps/nocodb/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/nocodb)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/nocodb)

[![NocoDB met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je NocoDB snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

NocoDB is an open source NoCode platform that turns any database into a smart spreadsheet, alternative to Airtable.

* Connect to new/existing SQL database and turn them into spreadsheet
* Create grid view, gallery view, kanban view and calendar view on top your data
* Search, sort, filter columns and rows with ultra ease
* Invite your team with fine grained Access Control
* Share views publicly and also with password protection
* Provides REST & GraphQL APIs with Swagger & GraphiQL GUI


**Geleverde versie:** 0.260.1~ynh1

**Demo:** <https://www.nocodb.com/demos>

## Schermafdrukken

![Schermafdrukken van NocoDB](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://www.nocodb.com>
- Upstream app codedepot: <https://github.com/nocodb/nocodb>
- YunoHost-store: <https://apps.yunohost.org/app/nocodb>
- Meld een bug: <https://github.com/YunoHost-Apps/nocodb_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
of
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
