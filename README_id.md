<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# NocoDB untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/nocodb)](https://ci-apps.yunohost.org/ci/apps/nocodb/)
![Status kerja](https://apps.yunohost.org/badge/state/nocodb)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/nocodb)

[![Pasang NocoDB dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang NocoDB secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

NocoDB is an open source NoCode platform that turns any database into a smart spreadsheet, alternative to Airtable.

* Connect to new/existing SQL database and turn them into spreadsheet
* Create grid view, gallery view, kanban view and calendar view on top your data
* Search, sort, filter columns and rows with ultra ease
* Invite your team with fine grained Access Control
* Share views publicly and also with password protection
* Provides REST & GraphQL APIs with Swagger & GraphiQL GUI


**Versi terkirim:** 0.260.1~ynh1

**Demo:** <https://www.nocodb.com/demos>

## Tangkapan Layar

![Tangkapan Layar pada NocoDB](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.nocodb.com>
- Depot kode aplikasi hulu: <https://github.com/nocodb/nocodb>
- Gudang YunoHost: <https://apps.yunohost.org/app/nocodb>
- Laporkan bug: <https://github.com/YunoHost-Apps/nocodb_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
atau
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
