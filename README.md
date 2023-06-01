Домашнее задание к занятию «Работа с данными (DDL/DML)» SKOPKIN ILYA

Задание 1
1.1. Поднимите чистый инстанс MySQL версии 8.0+. Можно использовать локальный сервер или контейнер Docker.

1.2. Создайте учётную запись sys_temp.

1.3. Выполните запрос на получение списка пользователей в базе данных. (скриншот)

1.4. Дайте все права для пользователя sys_temp.

1.5. Выполните запрос на получение списка прав для пользователя sys_temp. (скриншот)

1.6. Переподключитесь к базе данных от имени sys_temp.

Для смены типа аутентификации с sha2 используйте запрос:

ALTER USER 'sys_test'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
1.6. По ссылке https://downloads.mysql.com/docs/sakila-db.zip скачайте дамп базы данных.

1.7. Восстановите дамп в базу данных.

1.8. При работе в IDE сформируйте ER-диаграмму получившейся базы данных. При работе в командной строке используйте команду для получения всех таблиц базы данных. (скриншот)

Результатом работы должны быть скриншоты обозначенных заданий, а также простыня со всеми запросами.



1.2  ![alt text](https://github.com/matiz86/git_hw-12.2/blob/main/Screenshot_10.jpg)
 
1.3  ![alt text](https://github.com/matiz86/git_hw-12.2/blob/main/Screenshot_2.jpg)
 
1.4  ![alt text](https://github.com/matiz86/git_hw-12.2/blob/main/Screenshot_1.jpg)

1.5  ![alt text](https://github.com/matiz86/git_hw-12.2/blob/main/Screenshot_3.jpg)

1.8  ![alt text](https://github.com/matiz86/git_hw-12.2/blob/main/Screenshot_5.jpg)

Задание 2
Составьте таблицу, используя любой текстовый редактор или Excel, в которой должно быть два столбца: в первом должны быть названия таблиц восстановленной базы, во втором названия первичных ключей этих таблиц. Пример: (скриншот/текст)


![alt text](https://github.com/matiz86/git_hw-12.2/blob/main/Screenshot_6.jpg)
