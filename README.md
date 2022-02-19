<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# NocoDB for YunoHost

[![Integration level](https://dash.yunohost.org/integration/nocodb.svg)](https://dash.yunohost.org/appci/app/nocodb) ![](https://ci-apps.yunohost.org/ci/badges/nocodb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/nocodb.maintain.svg)  
[![Install NocoDB with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install NocoDB quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

NocoDB is an open source NoCode platform that turns any database into a smart spreadsheet, alternative to Airtable.

* Connect to new/existing SQL database and turn them into spreadsheet.
* Create grid view, gallery view, kanban view and calendar view on top your data
* Search, sort, filter columns and rows with ultra ease
* Invite your team with fine grained Access Control
* Share views publicly and also with password protection
* Provides REST & GraphQL APIs with Swagger & GraphiQL GUI

*(from NocoDB's website)*


**Shipped version:** 0.84.12~ynh1

**Demo:** https://www.nocodb.com/demos

## Screenshots

![](./doc/screenshots/example.png)

## Disclaimers / important information

NocoDB has its own authentication system which does not rely on YunoHost's SSO or LDAP server.
  * You can make it public, especially if you need its API.
  * You will need to create the first admin right after installation.

## Documentation and resources

* Official app website: https://www.nocodb.com/
* Upstream app code repository: https://github.com/nocodb/nocodb
* YunoHost documentation for this app: https://yunohost.org/app_nocodb
* Report a bug: https://github.com/YunoHost-Apps/nocodb_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
or
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps