Небольшое REST-API с 4 основными методами запросов (get, put, patch, delete) для таблиц вида 
(id, имя клиента, номер телефона)&(id, техника, цена, идентификатор со ссылкой на ключ id в 1 табице).
Помимо основых запросов для таблиц были написаны get-запросы на основе задания - возврат из базы данных вида "{Клиент {номер телефона} 
[{цена, техника},{...}]}
Приложение выполнено на основе Flask и sqlalchemy, протестировано с помощью postman в субд Postgresql и Mysql.
Внутри репозитория лежит txt файл "SQL-Scripts" с кодом для двух субд - mysql и postgresql ( Создание бд, таблиц и заполнение).
В файлике config.py лежит небольшое пояснение по подключению.