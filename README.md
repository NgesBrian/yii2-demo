Yii 2 Demo Template
===============================

Yii 2 Single Project Template is a skeleton [Yii 2](http://www.yiiframework.com/) application best for
developing complex Web applications with multiple tiers.

The template includes three tiers: front end, back end, and console, each of which
is a separate Yii application.

The template is designed to work in a team development environment. It supports
deploying the application in different environments.

[![Latest Stable Version](https://poser.pugx.org/yiisoft/yii2-app-advanced/v/stable.png)](https://packagist.org/packages/yiisoft/yii2-app-advanced)
[![Total Downloads](https://poser.pugx.org/yiisoft/yii2-app-advanced/downloads.png)](https://packagist.org/packages/yiisoft/yii2-app-advanced)
[![Build Status](https://travis-ci.org/yiisoft/yii2-app-advanced.svg?branch=master)](https://travis-ci.org/yiisoft/yii2-app-advanced)

DIRECTORY STRUCTURE
-------------------

```
assets/              contains application assets such as JavaScript and CSS
protected
    assets/              contains application assets such as JavaScript and CSS
    command/             contains console command classes
    config/              contains app configurations
    controllers/         contains Web controller classes
    models/              contains app-specific model classes
    runtime/             contains files generated during runtime
    views/               contains view files for the Web application
    web/                 contains the entry script and Web resources
    widgets/             contains app widgets
vendor/                  contains dependent 3rd-party packages
environments/            contains environment-based overrides
```

INSTALLATION
------------

```
composer create-project demoyii/yii2-demo myapp --prefer-dist
```