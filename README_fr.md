# PHPLicenseWatcher pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/phplicensewatcher.svg)](https://dash.yunohost.org/appci/app/phplicensewatcher) ![](https://ci-apps.yunohost.org/ci/badges/phplicensewatcher.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/phplicensewatcher.maintain.svg)  
[![Installer PHPLicenseWatcher avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phplicensewatcher)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer PHPLicenseWatcher rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

phpLicenseWatcher is a simple Web frontend to the FlexLM lmstat and lmdiag commands that gives information about the status of FlexLM servers. You can also get information about features and number of licenses available on a particular server. 

**Version incluse :** 1.9.2~ynh1

**Démo :** https://demo.example.com

## Captures d'écran

![](./doc/screenshots/screenshot1.png)

## Documentations et ressources

* Site officiel de l'app : https://example.com
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : https://yunohost.org/packaging_apps
* Dépôt de code officiel de l'app : https://github.com/rpi-dotcio/phpLicenseWatcher
* Documentation YunoHost pour cette app : https://yunohost.org/app_phplicensewatcher
* Signaler un bug : https://github.com/YunoHost-Apps/phplicensewatcher_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
ou
sudo yunohost app upgrade phplicensewatcher -u https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps