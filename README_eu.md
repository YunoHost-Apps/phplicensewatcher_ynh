<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# PHPLicenseWatcher YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/phplicensewatcher.svg)](https://dash.yunohost.org/appci/app/phplicensewatcher) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/phplicensewatcher.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/phplicensewatcher.maintain.svg)

[![Instalatu PHPLicenseWatcher YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phplicensewatcher)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek PHPLicenseWatcher YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

phpLicenseWatcher is a simple Web frontend to the FlexLM lmstat and lmdiag commands that gives information about the status of FlexLM servers. You can also get information about features and number of licenses available on a particular server.

### Features

- Shows the health of a license server or a group of them
- Check which licenses are being used and who is currently using them
- Get a listing of licenses, their expiration days and number of days to expiration
- E-mail alert of licenses that will expire within certain time period ie. within next 10 days.
- Monitors server utilization
- Provides usage charts


**Paketatutako bertsioa:** 2024.04.26~ynh1

## Pantaila-argazkiak

![PHPLicenseWatcher(r)en pantaila-argazkia](./doc/screenshots/screenshot1.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <http://phplicensewatch.sourceforge.net>
- Administratzaileen dokumentazio ofiziala: <https://phplicensewatch.sourceforge.io/index.html#Documentation>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/rpi-dotcio/phpLicenseWatcher>
- YunoHost Denda: <https://apps.yunohost.org/app/phplicensewatcher>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/phplicensewatcher_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
edo
sudo yunohost app upgrade phplicensewatcher -u https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
