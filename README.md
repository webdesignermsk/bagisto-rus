<p align="center">
<a href="http://www.bagisto.com"><img src="https://bagisto.com/wp-content/themes/bagisto/images/logo.png" alt="Total Downloads"></a>
</p>

<p align="center">
<a href="https://packagist.org/packages/bagisto/bagisto"><img src="https://poser.pugx.org/bagisto/bagisto/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/bagisto/bagisto"><img src="https://poser.pugx.org/bagisto/bagisto/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/bagisto/bagisto"><img src="https://poser.pugx.org/bagisto/bagisto/license.svg" alt="License"></a>
<a href="#backers"><img src="https://opencollective.com/bagisto/backers/badge.svg" alt="Backers on Open Collective"></a>
<a href="#sponsors"><img src="https://opencollective.com/bagisto/sponsors/badge.svg" alt="Sponsors on Open Collective"></a>
</p>

### 1. Описание:

Bagisto - eCommerce платформа с открытым исходным кодом для создания Вашего бизнеса, построенная на популярном PHP фреймворке - Laravel.

### 2. Документация:

#### Официальный сайт [https://devdocs.bagisto.com](https://devdocs.bagisto.com)

### 3. Необходимое окружение:

* **Сервер**: Apache 2 или NGINX
* **PHP**: 7.1.17 или выше.
* **Для пользователей MySQL**: 5.7.23 или выше.
* **Для пользователей MariaDB**: 10.2.7 или выше.
* **Node**: 8.11.3 LTS или выше.
* **Composer**: 1.6.5 или выше.

### 4. Установка и конфигурация:

1. Выполняем git clone в консоле:
~~~
$ git clone https://github.com/JOKER-THE/bagisto-rus.git
~~~

2. Используя Composer, собираем autoload и загружаем подключаемые библиотеки:
~~~
$ composer install
~~~

3. Открываем сайт через браузер.

4. При первом запуске сайта откроется Installer, выполняем весь процесс установки.

5. Разрешаем копировать шаблоны пакета в папку `resources/views/vendor`:
~~~
$ php artisan vendor:publish
~~~

6. Создаем символьную ссылку для хранения файлов:
~~~
$ php artisan storage:link
~~~

7. Обновляем файлы автозагрузчика Composer:
~~~
$ composer dump-autoload
~~~

8. Разрешаем системе запись и чтение файлов из `storage`:
~~~
$ chmod -R ug+rwx storage
~~~
