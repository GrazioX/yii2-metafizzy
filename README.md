Metafizzy Asset Bundle
======================
Yii2 asset bundle wrapper around David DeSandro javascript libraries masonry, isotope, packery, and draggabilly.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist devleaks/yii2-metafizzy "*"
```

or add

```
"devleaks/yii2-metafizzy": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?php
use devleaks\introjs\IntroJSAsset;

IsotopeAsset::register($this);

or

MasonryAsset::register($this);

or

PackeryAsset::register($this);

or

DraggabillyAsset::register($this);
