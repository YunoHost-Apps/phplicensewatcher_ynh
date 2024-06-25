<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# PHPLicenseWatcher para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/phplicensewatcher.svg)](https://dash.yunohost.org/appci/app/phplicensewatcher) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/phplicensewatcher.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/phplicensewatcher.maintain.svg)

[![Instalar PHPLicenseWatcher con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phplicensewatcher)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarPHPLicenseWatcher rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

phpLicenseWatcher is a simple Web frontend to the FlexLM lmstat and lmdiag commands that gives information about the status of FlexLM servers. You can also get information about features and number of licenses available on a particular server.

### Features

- Shows the health of a license server or a group of them
- Check which licenses are being used and who is currently using them
- Get a listing of licenses, their expiration days and number of days to expiration
- E-mail alert of licenses that will expire within certain time period ie. within next 10 days.
- Monitors server utilization
- Provides usage charts


**Versión actual:** 2024.06.24~ynh1

## Capturas

![Captura de PHPLicenseWatcher](./doc/screenshots/screenshot1.png)

## Documentaciones y recursos

- Sitio web oficial: <http://phplicensewatch.sourceforge.net>
- Documentación administrador oficial: <https://phplicensewatch.sourceforge.io/index.html#Documentation>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/rpi-dotcio/phpLicenseWatcher>
- Catálogo YunoHost: <https://apps.yunohost.org/app/phplicensewatcher>
- Reportar un error: <https://github.com/YunoHost-Apps/phplicensewatcher_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
o
sudo yunohost app upgrade phplicensewatcher -u https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
