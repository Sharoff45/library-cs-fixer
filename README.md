# library-cs-fixer

# Установка

composer:

    composer require --dev sharoff45/library-cs-fixer

Скопируйте правила из примера:

    cp ./vendor/sharoff45/library-cs-fixer/.php_cs.dist ./

# Применение:

для внесения исправлений в проект согласно правилам Code Style


    bin/php-cs-fixer fix

p.s. по умолчанию в конфиг для проверки добавляются директории `src` и `tests`

для проверки файлов на соответствие требованиям Code Style


    bin/php-cs-fixer fix -v --dry-run --stop-on-violation --using-cache=no src


Подробноую информацию об использовании можно найти здесь https://github.com/FriendsOfPHP/PHP-CS-Fixer
