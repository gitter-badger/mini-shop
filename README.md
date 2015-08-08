Yii 2 Мини интернет магазин
============================

[![Join the chat at https://gitter.im/softua/mini-shop](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/softua/mini-shop?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Yii 2 Basic Project Template is a skeleton [Yii 2](http://www.yiiframework.com/) application best for
rapidly creating small projects.

[![Latest Stable Version](https://poser.pugx.org/yiisoft/yii2-app-basic/v/stable.png)](https://packagist.org/packages/yiisoft/yii2-app-basic)
[![Total Downloads](https://poser.pugx.org/yiisoft/yii2-app-basic/downloads.png)](https://packagist.org/packages/yiisoft/yii2-app-basic)
[![Build Status](https://travis-ci.org/yiisoft/yii2-app-basic.svg?branch=master)](https://travis-ci.org/yiisoft/yii2-app-basic)

DIRECTORY STRUCTURE
-------------------

      assets/             contains assets definition
      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      mail/               contains view files for e-mails
      models/             contains model classes
      runtime/            contains files generated during runtime
      tests/              contains various tests for the basic application
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      web/                contains the entry script and Web resources
      locals.php          в этом файле объявлены константы, необходимые для конфигурации приложения:
            COOKIE_SECRET   -   для cookieValidationKey
            DB_DSN          -   строка соединения с БД
            DB_USERNAME     -   пользователь БД
            DB_PASSWORD     -   пароль БД


REQUIREMENTS
------------

Написать мини - интернет магазин, содержащий товары, которые распределены по категориям и с 
возможностью добавлять товары в корзину. Всю информацию хранить в базе данных.

Административная часть должна давать возможность:
    
 - добавлять категорию товаров;
 - добавлять товар и связывать его с категорией;
 - редактирование категории/товара;

На сайте реализовать каталог для просмотра товаров, с меню категорий. При выборе категории попадаем на ее список товаров.

#Реализовать:

 - добавление товара в корзину;
 - все операции в корзине (добавление товара из корзины, увеличение/уменьшение количества, кнопка "оформить", но при 
ее  нажатии  товары  просто  сохраняются  в  отдельную  таблицу,  а  в  админке  можно  будет 
просмотреть какие товары заказали).