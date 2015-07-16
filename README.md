Autoload asses
==============
Autoload assets on pjax page

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist pistej/yii2-autoload-assets "*"
```

or add

```
"pistej/yii2-autoload-assets": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \pistej\autoloadssets\AutoloadExample::widget(); ?>```