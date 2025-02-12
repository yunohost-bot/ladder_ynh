<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Ladder pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/ladder.svg)](https://dash.yunohost.org/appci/app/ladder) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/ladder.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/ladder.maintain.svg)

[![Installer Ladder avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ladder)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Ladder rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

La liberté d'information est un pilier essentiel de la démocratie et de la prise de décision éclairée. Bien que les organisations médiatiques aient des intérêts financiers légitimes, il est crucial de trouver un équilibre entre la rentabilité et le droit du public à accéder à l'information. La prolifération des paywalls suscite des inquiétudes quant à l'érosion de cette liberté fondamentale, et il est impératif pour la société de trouver des moyens innovants de préserver l'accès à des informations vitales sans compromettre la durabilité du journalisme. Dans un monde où la connaissance devrait être partagée et non marchandisée, les paywalls devraient être examinés de manière critique pour s'assurer qu'ils ne sapent pas les principes d'une société ouverte et informée.

Certains sites ne rendent pas leur contenu accessible aux moteurs de recherche, ce qui signifie que le proxy ne peut pas accéder au contenu. Une version future tentera de récupérer le contenu depuis le cache de Google.

Certains sites peuvent afficher des images manquantes ou rencontrer des problèmes de mise en forme. Cela peut être attribué à la dépendance du site à JavaScript ou CSS pour le chargement d'images et de ressources, ce qui présente une limitation lorsqu'il est accédé via ce proxy. Si vous préférez une expérience complète, veuillez envisager d'acheter un abonnement pour le site.

**Version incluse :** 0.0.21~ynh2

## Captures d’écran

![Capture d’écran de Ladder](./doc/screenshots/example.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/everywall/ladder>
- YunoHost Store : <https://apps.yunohost.org/app/ladder>
- Signaler un bug : <https://github.com/YunoHost-Apps/ladder_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/ladder_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ladder_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ladder -u https://github.com/YunoHost-Apps/ladder_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
