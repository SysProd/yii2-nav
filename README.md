Nav for AdminLTE
================
Nav for AdminLTE backend theme asset bundle for Yii 2.0 Framework

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist SysProd/yii2-nav "*"
```

or add

```
"SysProd/yii2-nav": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \SysProd\nav\Nav::widget(); ?>
<?= \SysProd\nav\NavBar::widget(); ?>
<?= \SysProd\nav\NavUser::widget(); ?>
```