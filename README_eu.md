<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# NocoDB YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/nocodb)](https://ci-apps.yunohost.org/ci/apps/nocodb/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/nocodb)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/nocodb)

[![Instalatu NocoDB YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek NocoDB YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

NocoDB is an open source NoCode platform that turns any database into a smart spreadsheet, alternative to Airtable.

* Connect to new/existing SQL database and turn them into spreadsheet
* Create grid view, gallery view, kanban view and calendar view on top your data
* Search, sort, filter columns and rows with ultra ease
* Invite your team with fine grained Access Control
* Share views publicly and also with password protection
* Provides REST & GraphQL APIs with Swagger & GraphiQL GUI


**Paketatutako bertsioa:** 0.260.1~ynh1

**Demoa:** <https://www.nocodb.com/demos>

## Pantaila-argazkiak

![NocoDB(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.nocodb.com>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/nocodb/nocodb>
- YunoHost Denda: <https://apps.yunohost.org/app/nocodb>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/nocodb_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
edo
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
