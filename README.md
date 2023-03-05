<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Grav for YunoHost

[![Integration level](https://dash.yunohost.org/integration/grav.svg)](https://dash.yunohost.org/appci/app/grav) ![Working status](https://ci-apps.yunohost.org/ci/badges/grav.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/grav.maintain.svg)

[![Install Grav with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=grav)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Grav quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Grav is a modern open source flat-file CMS.


**Shipped version:** 1.7.39.4~ynh2

**Demo:** https://getgrav.org/downloads/themes

## Screenshots

![Screenshot of Grav](./doc/screenshots/grav.jpg)

## Disclaimers / important information

* You can access the administration panel at `yourdomain.tld/path/admin`. Users created within YunoHost can log in, provided their were given the appropriate permissions:
  * To make users administrators, give them the `grav.admin` permission.
  * To allow users to log in, without extended rights, give them the `grav.user` permission.
* Grav offers an SSH or SFTP access, which can be enabled in its YunoHost admin configuration panel.
  * You can thus use its GPM command line binary.
    Refer to is documentation, but bear in mind you need to call it by specifying the PHP version used by the app:
    `php7.3 bin/grav ...` or `php7.3 bin/gpm ...`
* You can install plugins through the admin panel, or through the GPM.
* If installing Grav at the root of a domain, bear in mind that paths starting by `/yunohost` are reserved.

## Documentation and resources

* Official app website: <https://www.getgrav.org/>
* Official admin documentation: <https://learn.getgrav.org>
* Upstream app code repository: <https://github.com/getgrav/grav>
* YunoHost documentation for this app: <https://yunohost.org/app_grav>
* Report a bug: <https://github.com/YunoHost-Apps/grav_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/grav_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/grav_ynh/tree/testing --debug
or
sudo yunohost app upgrade grav -u https://github.com/YunoHost-Apps/grav_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
