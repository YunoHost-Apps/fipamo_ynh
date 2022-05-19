# Fipamo pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/fipamo.svg)](https://dash.yunohost.org/appci/app/fipamo) ![](https://ci-apps.yunohost.org/ci/badges/fipamo.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/fipamo.maintain.svg)  
[![Installer Fipamo avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=fipamo)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Fipamo rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

The Fipamo project was born from a need for a simple, easy to use no data blog platform that doesn’t require much effort to set up and maintain. Fipamo uses Markdown to handle posts and renders them to flat html so you can serve them from anywhere. No complicated set ups. No long list of dependencies. Just write and publish.


**Version incluse :** 2.5.0~ynh1

**Démo :** https://demo.example.com

## Captures d'écran

![](./doc/screenshots/dash-index.png)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentations et ressources

* Site officiel de l'app : https://fipamo.blog
* Documentation officielle de l'admin : https://yunohost.org/packaging_apps
* Dépôt de code officiel de l'app : https://code.playvicio.us/Are0h/Fipamo
* Documentation YunoHost pour cette app : https://yunohost.org/app_fipamo
* Signaler un bug : https://github.com/YunoHost-Apps/fipamo_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/fipamo_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/fipamo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade fipamo -u https://github.com/YunoHost-Apps/fipamo_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps