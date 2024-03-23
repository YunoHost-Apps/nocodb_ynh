<!--
Nota bene: ce README est automatiquement généré par https://github.com/YunoHost/apps/tree/master/tools/readme_generator
Il ne doit pas être modifié à la main.
-->

# NocoDB pour YunoHost

[![Niveau d'intégration ](https://dash.yunohost.org/integration/nocodb.svg)](https://dash.yunohost.org/appci/app/nocodb) ![Status du fonctionnement](https://ci-apps.yunohost.org/ci/badges/nocodb.status.svg) ![Statut demaintenance](https://ci-apps.yunohost.org/ci/badges/nocodb.maintain.svg)

[![Installer NocoDB avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer NocoDB rapidement et simplement sur un serveur YunoHost.
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d'ensemble

NocoDB is an open source NoCode platform that turns any database into a smart spreadsheet, alternative to Airtable.

* Connect to new/existing SQL database and turn them into spreadsheet
* Create grid view, gallery view, kanban view and calendar view on top your data
* Search, sort, filter columns and rows with ultra ease
* Invite your team with fine grained Access Control
* Share views publicly and also with password protection
* Provides REST & GraphQL APIs with Swagger & GraphiQL GUI

**Version incluse :** 0.204.8~ynh1

**Démo:** <https://www.nocodb.com/demos>

## Captures d'écran

![Capture d'écran de NocoDB](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.nocodb.com>
- Dépôt de code officiel de l’app : <https://github.com/nocodb/nocodb>
- YunoHost Store : <https://apps.yunohost.org/app/nocodb>
- Signaler un bug : <https://github.com/YunoHost-Apps/nocodb_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche branch](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing),


Pour essayer la branche testing, procédez comme suit.

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
or
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** <https://yunohost.org/packaging_apps>
