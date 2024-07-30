# Домашнее задание к занятию "`GIT`" - `Dima Kolb`

## Задание 1

#### Сотрудники (Employees):

* идентификатор (id): первичный ключ, serial
* фио (name): varchar(100)
* идентификатор должности (id_position): внешний ключ, integer
* идентификатор адреса (id_address): внешний ключ, integer


#### Структурные подразделения (Structural Units):

* идентификатор (id_units): первичный ключ, serial
* название (name): varchar(100)


#### Должности (Positions):

* идентификатор (id_position): первичный ключ, serial
* название (name): varchar(100)


#### Проекты (Projects):

* идентификатор (id_projects): первичный ключ, serial
* название (name): varchar(100)


#### Адреса (Unit Address):

* идентификатор (id_full_address): первичный ключ, serial
* город (city): varchar(100)


#### Типы подразделений (Unit Types):

* идентификатор (id_type): первичный ключ, serial
* название (name): varchar(100)
