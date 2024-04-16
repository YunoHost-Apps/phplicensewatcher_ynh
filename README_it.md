<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# PHPLicenseWatcher per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/phplicensewatcher.svg)](https://dash.yunohost.org/appci/app/phplicensewatcher) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/phplicensewatcher.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/phplicensewatcher.maintain.svg)

[![Installa PHPLicenseWatcher con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phplicensewatcher)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare PHPLicenseWatcher su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

phpLicenseWatcher is a simple Web frontend to the FlexLM lmstat and lmdiag commands that gives information about the status of FlexLM servers. You can also get information about features and number of licenses available on a particular server.

### Features

- Shows the health of a license server or a group of them
- Check which licenses are being used and who is currently using them
- Get a listing of licenses, their expiration days and number of days to expiration
- E-mail alert of licenses that will expire within certain time period ie. within next 10 days.
- Monitors server utilization
- Provides usage charts


**Versione pubblicata:** 2.210916~ynh2

## Screenshot

![Screenshot di PHPLicenseWatcher](./doc/screenshots/screenshot1.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <http://phplicensewatch.sourceforge.net>
- Documentazione ufficiale per gli amministratori: <https://phplicensewatch.sourceforge.io/index.html#Documentation>
- Repository upstream del codice dell’app: <https://github.com/rpi-dotcio/phpLicenseWatcher>
- Store di YunoHost: <https://apps.yunohost.org/app/phplicensewatcher>
- Segnala un problema: <https://github.com/YunoHost-Apps/phplicensewatcher_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
o
sudo yunohost app upgrade phplicensewatcher -u https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
