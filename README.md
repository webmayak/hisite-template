# HiSite Template

**HiSite Project Template**

[![Latest Stable Version](https://poser.pugx.org/hiqdev/hisite-template/v/stable)](https://packagist.org/packages/hiqdev/hisite-template)
[![Total Downloads](https://poser.pugx.org/hiqdev/hisite-template/downloads)](https://packagist.org/packages/hiqdev/hisite-template)
[![Build Status](https://img.shields.io/travis/hiqdev/hisite-template.svg)](https://travis-ci.org/hiqdev/hisite-template)
[![Scrutinizer Code Coverage](https://img.shields.io/scrutinizer/coverage/g/hiqdev/hisite-template.svg)](https://scrutinizer-ci.com/g/hiqdev/hisite-template/)
[![Scrutinizer Code Quality](https://img.shields.io/scrutinizer/g/hiqdev/hisite-template.svg)](https://scrutinizer-ci.com/g/hiqdev/hisite-template/)
[![Dependency Status](https://www.versioneye.com/php/hiqdev:hisite-template/dev-master/badge.svg)](https://www.versioneye.com/php/hiqdev:hisite-template/dev-master)

[HiSite] is a base project for building modular [Yii2] web applications from plugins.

This package is a template to start your HiSite project with.

It includes:

- [hisite] - HiSite basic project
- [yii2-theme-original] - Yii2 original theme
- [yii2-pnotify] - JQuery [PNotify] extension
- [yii2-language] - language switcher
- [yii2-monitoring] - application monitoring

The project uses [hidev] tool to automate repetitive tasks:

- generate and keep up to date package files: README, LICENSE, .gitignore, composer.json
- keep CHANGELOG file with [chkipper]
- generate and deploy Nginx virtual host config file
- run standard tasks such as running tests and `php-cs-fixer`
- substitute `yii` console script

[yii2]:                 http://www.yiiframework.com/
[hidev]:                https://github.com/hiqdev/hidev
[HiSite]:               https://github.com/hiqdev/hisite
[yii2-theme-original]:  https://github.com/hiqdev/yii2-theme-original
[yii2-pnotify]:         https://github.com/hiqdev/yii2-thememanager
[yii2-language]:        https://github.com/hiqdev/yii2-language
[yii2-monitoring]:      https://github.com/hiqdev/yii2-monitoring
[chkipper]:             https://github.com/hiqdev/chkipper
[pnotify]:              https://github.com/sciactive/pnotify

## Installation

The preferred way to install this project is through [composer](http://getcomposer.org/download/).

```sh
php composer.phar create-project "hiqdev/hisite-template:*" directory2install
```

## License

This project is released under the terms of the BSD-3-Clause [license](LICENSE).
Read more [here](http://choosealicense.com/licenses/bsd-3-clause).

Copyright © 2016-2017, HiQDev (http://hiqdev.com/)
