<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# NocoDB per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/nocodb)](https://ci-apps.yunohost.org/ci/apps/nocodb/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/nocodb)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/nocodb)

[![Instal·la NocoDB amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar NocoDB de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

NocoDB is an open source NoCode platform that turns any database into a smart spreadsheet, alternative to Airtable.

* Connect to new/existing SQL database and turn them into spreadsheet
* Create grid view, gallery view, kanban view and calendar view on top your data
* Search, sort, filter columns and rows with ultra ease
* Invite your team with fine grained Access Control
* Share views publicly and also with password protection
* Provides REST & GraphQL APIs with Swagger & GraphiQL GUI


**Versió inclosa:** 0.262.5~ynh1

**Demo:** <https://www.nocodb.com/demos>

## Captures de pantalla

![Captures de pantalla de NocoDB](./doc/screenshots/screenshot.png)

## Documentació i recursos

- Lloc web oficial de l'aplicació: <https://www.nocodb.com>
- Repositori oficial del codi de l'aplicació: <https://github.com/nocodb/nocodb>
- Botiga YunoHost: <https://apps.yunohost.org/app/nocodb>
- Reportar un error: <https://github.com/YunoHost-Apps/nocodb_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
o
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>
