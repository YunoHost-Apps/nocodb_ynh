<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# NocoDB per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/nocodb.svg)](https://dash.yunohost.org/appci/app/nocodb) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/nocodb.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/nocodb.maintain.svg)

[![Installa NocoDB con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare NocoDB su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

NocoDB is an open source NoCode platform that turns any database into a smart spreadsheet, alternative to Airtable.

* Connect to new/existing SQL database and turn them into spreadsheet
* Create grid view, gallery view, kanban view and calendar view on top your data
* Search, sort, filter columns and rows with ultra ease
* Invite your team with fine grained Access Control
* Share views publicly and also with password protection
* Provides REST & GraphQL APIs with Swagger & GraphiQL GUI


**Versione pubblicata:** 0.204.4~ynh1

**Prova:** <https://www.nocodb.com/demos>

## Screenshot

![Screenshot di NocoDB](./doc/screenshots/screenshot.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://www.nocodb.com>
- Repository upstream del codice dell’app: <https://github.com/nocodb/nocodb>
- Store di YunoHost: <https://apps.yunohost.org/app/nocodb>
- Segnala un problema: <https://github.com/YunoHost-Apps/nocodb_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
o
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
