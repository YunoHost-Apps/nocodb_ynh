<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# NocoDB dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/nocodb)](https://ci-apps.yunohost.org/ci/apps/nocodb/)
![Status działania](https://apps.yunohost.org/badge/state/nocodb)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/nocodb)

[![Zainstaluj NocoDB z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację NocoDB na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

NocoDB is an open source NoCode platform that turns any database into a smart spreadsheet, alternative to Airtable.

* Connect to new/existing SQL database and turn them into spreadsheet
* Create grid view, gallery view, kanban view and calendar view on top your data
* Search, sort, filter columns and rows with ultra ease
* Invite your team with fine grained Access Control
* Share views publicly and also with password protection
* Provides REST & GraphQL APIs with Swagger & GraphiQL GUI


**Dostarczona wersja:** 0.260.1~ynh1

**Demo:** <https://www.nocodb.com/demos>

## Zrzuty ekranu

![Zrzut ekranu z NocoDB](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://www.nocodb.com>
- Repozytorium z kodem źródłowym: <https://github.com/nocodb/nocodb>
- Sklep YunoHost: <https://apps.yunohost.org/app/nocodb>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/nocodb_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
lub
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
