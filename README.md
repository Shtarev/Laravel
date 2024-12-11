Здесь начальная и относительно полная сборка Laravel с модулями, которые я считаю более-менее потребными


PHP Version 8.2.26

mysqld  Ver 8.0.40

Laravel v11.28.1

Пример домена: http://laravel.loc


Установлены:

админка Voyager

    Вход в админку:
    
        laravel.loc/admin
        
        email: admin@admin.com
        
        password: password
        

пагинация nicolaslopezj

vue

    ui vue --auth
    
    vue-router
    
    vue-axios
    
    vuex
    
    laravel-vue-pagination
    

tailwind

vite

Всё установленное имеет базовую настройку


После клонирования

настроить .env(здесь пример):

APP_URL=http://laravel.loc

//...

DB_CONNECTION=mysql

DB_HOST=127.0.0.1

DB_PORT=3306

DB_DATABASE=laravel

DB_USERNAME=root

DB_PASSWORD=2222


сиздать пустую mysql базу с именем laravel с пользователем root и паролем 2222


ввести в консоль:

sudo chmod -R 777 storage

sudo chmod -R 777 bootstrap/cache

composer install

npm install

php artisan migrate

php artisan key:generate

##################################

Сайт доступен: http://laravel.loc

Админка: http://laravel.loc/admin
