<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# PHPLicenseWatcher voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/phplicensewatcher)](https://ci-apps.yunohost.org/ci/apps/phplicensewatcher/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/phplicensewatcher)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/phplicensewatcher)

[![PHPLicenseWatcher met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phplicensewatcher)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je PHPLicenseWatcher snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

phpLicenseWatcher is a simple Web frontend to the FlexLM lmstat and lmdiag commands that gives information about the status of FlexLM servers. You can also get information about features and number of licenses available on a particular server.

### Features

- Shows the health of a license server or a group of them
- Check which licenses are being used and who is currently using them
- Get a listing of licenses, their expiration days and number of days to expiration
- E-mail alert of licenses that will expire within certain time period ie. within next 10 days.
- Monitors server utilization
- Provides usage charts


**Geleverde versie:** 2025.03.09~ynh1

## Schermafdrukken

![Schermafdrukken van PHPLicenseWatcher](./doc/screenshots/screenshot1.png)

## Documentatie en bronnen

- Officiele website van de app: <http://phplicensewatch.sourceforge.net>
- Officiele beheerdersdocumentatie: <https://phplicensewatch.sourceforge.io/index.html#Documentation>
- Upstream app codedepot: <https://github.com/rpi-dotcio/phpLicenseWatcher>
- YunoHost-store: <https://apps.yunohost.org/app/phplicensewatcher>
- Meld een bug: <https://github.com/YunoHost-Apps/phplicensewatcher_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
of
sudo yunohost app upgrade phplicensewatcher -u https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
