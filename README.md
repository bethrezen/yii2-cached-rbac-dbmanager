Cached DBManager for yii2 RBAC
==============================
Allows caching of permissions in yii\rbac\DbManager 

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist bethrezen/yii2-cached-rbac-dbmanager "*"
```

or add

```
"bethrezen/yii2-cached-rbac-dbmanager": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply configure your application to use `\bethrezen\CachedDbManager`:

```

'components' => [
    // the rest of your components section
    'authManager' => [
            'class'=>'\bethrezen\CachedDbManager',
        ],
]

```