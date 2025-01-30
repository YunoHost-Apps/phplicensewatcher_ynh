<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# PHPLicenseWatcher para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/phplicensewatcher)](https://ci-apps.yunohost.org/ci/apps/phplicensewatcher/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/phplicensewatcher)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/phplicensewatcher)

[![Instalar PHPLicenseWatcher con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phplicensewatcher)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar PHPLicenseWatcher de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

phpLicenseWatcher is a simple Web frontend to the FlexLM lmstat and lmdiag commands that gives information about the status of FlexLM servers. You can also get information about features and number of licenses available on a particular server.

### Features

- Shows the health of a license server or a group of them
- Check which licenses are being used and who is currently using them
- Get a listing of licenses, their expiration days and number of days to expiration
- E-mail alert of licenses that will expire within certain time period ie. within next 10 days.
- Monitors server utilization
- Provides usage charts


**Versión proporcionada:** 2024.10.01~ynh1

## Capturas de pantalla

![Captura de pantalla de PHPLicenseWatcher](./doc/screenshots/screenshot1.png)

## Documentación e recursos

- Web oficial da app: <http://phplicensewatch.sourceforge.net>
- Documentación oficial para admin: <https://phplicensewatch.sourceforge.io/index.html#Documentation>
- Repositorio de orixe do código: <https://github.com/rpi-dotcio/phpLicenseWatcher>
- Tenda YunoHost: <https://apps.yunohost.org/app/phplicensewatcher>
- Informar dun problema: <https://github.com/YunoHost-Apps/phplicensewatcher_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
ou
sudo yunohost app upgrade phplicensewatcher -u https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
