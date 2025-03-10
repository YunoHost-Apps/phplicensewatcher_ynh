<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# PHPLicenseWatcher untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/phplicensewatcher)](https://ci-apps.yunohost.org/ci/apps/phplicensewatcher/)
![Status kerja](https://apps.yunohost.org/badge/state/phplicensewatcher)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/phplicensewatcher)

[![Pasang PHPLicenseWatcher dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phplicensewatcher)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang PHPLicenseWatcher secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

phpLicenseWatcher is a simple Web frontend to the FlexLM lmstat and lmdiag commands that gives information about the status of FlexLM servers. You can also get information about features and number of licenses available on a particular server.

### Features

- Shows the health of a license server or a group of them
- Check which licenses are being used and who is currently using them
- Get a listing of licenses, their expiration days and number of days to expiration
- E-mail alert of licenses that will expire within certain time period ie. within next 10 days.
- Monitors server utilization
- Provides usage charts


**Versi terkirim:** 2025.03.09~ynh1

## Tangkapan Layar

![Tangkapan Layar pada PHPLicenseWatcher](./doc/screenshots/screenshot1.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <http://phplicensewatch.sourceforge.net>
- Dokumentasi admin resmi: <https://phplicensewatch.sourceforge.io/index.html#Documentation>
- Depot kode aplikasi hulu: <https://github.com/rpi-dotcio/phpLicenseWatcher>
- Gudang YunoHost: <https://apps.yunohost.org/app/phplicensewatcher>
- Laporkan bug: <https://github.com/YunoHost-Apps/phplicensewatcher_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
atau
sudo yunohost app upgrade phplicensewatcher -u https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
