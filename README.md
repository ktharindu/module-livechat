# M2 Live Chat Configuration (Part2)

## 1. Description

This module setup is basically the configuration of the Live Chat.
It will create system configuration field(s) and set default value(s).

## 2. How to install

### Install via composer (recommend)

Run the following command in Magento 2 root folder:

```
composer config repositories.ktharindu-module-livechat git git@github.com:ktharindu/module-livechat.git
composer require ktharindu/module-livechat dev-master
php bin/magento setup:upgrade
```

### Install ready-to-paste package

- Download package from [module-livechat-master.zip](https://github.com/ktharindu/module-livechat/archive/master.zip)
- Unzip it
- Upload it to the mentioned path: magento_root/app/code/Agt/
- Rename module-livechat-master folder to LiveChat
- Run the following command in Magento 2 root folder:
```
php bin/magento setup:upgrade
```
- Logout and Login again to avoid "Access denied" 404 error in system configuration.


### How to configure
Please setup the configuration as follows:
1. Login to magento backend
2. Click Stores -> Configuration
3. At the left corner panel, you'll find a Live Chat menu. Click it to expand it and you'll see Settings menu.
4. Click on Settings menu. It will display the Configuration screen for Live Chat.
5. Setup the relevant configurations accordingly and click on Save Config button.



