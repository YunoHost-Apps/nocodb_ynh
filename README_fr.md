<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# NocoDB pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/nocodb)](https://ci-apps.yunohost.org/ci/apps/nocodb/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/nocodb)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/nocodb)

[![Installer NocoDB avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nocodb)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer NocoDB rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

NocoDB est une plateforme NoCode open source qui transforme n'importe quelle base de données en une feuille de calcul intelligente, alternative à Airtable.

* Connectez-vous à une base de données SQL nouvelle/existante et transformez-la en feuille de calcul
* Créez une vue grille, une vue galerie, une vue kanban et une vue calendrier au-dessus de vos données
* Rechercher, trier, filtrer les colonnes et les lignes en toute simplicité
* Invitez votre équipe avec un contrôle d'accès précis
* Partagez vos vues publiquement et également avec une protection par mot de passe
* Fournit des API REST et GraphQL avec l'interface graphique Swagger et GraphiQL

**Version incluse :** 0.260.1~ynh1

**Démo :** <https://www.nocodb.com/demos>

## Captures d’écran

![Capture d’écran de NocoDB](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.nocodb.com>
- Dépôt de code officiel de l’app : <https://github.com/nocodb/nocodb>
- YunoHost Store : <https://apps.yunohost.org/app/nocodb>
- Signaler un bug : <https://github.com/YunoHost-Apps/nocodb_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade nocodb -u https://github.com/YunoHost-Apps/nocodb_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
