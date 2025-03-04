<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# PHPLicenseWatcher dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/phplicensewatcher)](https://ci-apps.yunohost.org/ci/apps/phplicensewatcher/)
![Status działania](https://apps.yunohost.org/badge/state/phplicensewatcher)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/phplicensewatcher)

[![Zainstaluj PHPLicenseWatcher z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phplicensewatcher)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację PHPLicenseWatcher na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

phpLicenseWatcher is a simple Web frontend to the FlexLM lmstat and lmdiag commands that gives information about the status of FlexLM servers. You can also get information about features and number of licenses available on a particular server.

### Features

- Shows the health of a license server or a group of them
- Check which licenses are being used and who is currently using them
- Get a listing of licenses, their expiration days and number of days to expiration
- E-mail alert of licenses that will expire within certain time period ie. within next 10 days.
- Monitors server utilization
- Provides usage charts


**Dostarczona wersja:** 2025.02.27~ynh1

## Zrzuty ekranu

![Zrzut ekranu z PHPLicenseWatcher](./doc/screenshots/screenshot1.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <http://phplicensewatch.sourceforge.net>
- Oficjalna dokumentacja dla administratora: <https://phplicensewatch.sourceforge.io/index.html#Documentation>
- Repozytorium z kodem źródłowym: <https://github.com/rpi-dotcio/phpLicenseWatcher>
- Sklep YunoHost: <https://apps.yunohost.org/app/phplicensewatcher>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/phplicensewatcher_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
lub
sudo yunohost app upgrade phplicensewatcher -u https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
