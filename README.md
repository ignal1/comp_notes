**[Demo](http://84.38.180.229:83)**

Учетные данные для входа в систему  
логин: `user@mail.com`  
пароль: 1

## Реализовано:

- Аутентификация

- Просмотр списка компаний всеми пользователями

- Создание компаний зарегистрированными пользователями

- Удаление компании тем пользователем, который ее создал

- Просмотр информации о компании

- Создание комментариев к каждому полю и компании в целом. Доступно только зарегистрированным пользователям

- Добавление комментария происходит без перезагрузки страницы. При этом новый комментарий можно сразу открыть или удалить

- Удалить комментарий может только его создатель. Удаление комментария происходит без перезагрузки страницы

- Адаптивная верстка

## Используемые технологии:

- Laravel

- jQuery

- AJAX

## Запуск проекта

Перед запуском приложения необходимо создать базу данных Postgres с именем **comp_notes**, пользователем **postgres** и паролем **postgres** и загрузить в нее данные из файла **dump.sql**.
Войти в систему можно под пользователем **user@mail.com** с паролем **1**.