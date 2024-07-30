# Домашнее задание к занятию "`GIT`" - `Dima Kolb`

## Задание 1

#### Сотрудники (Employees):

* идентификатор (id_name): первичный ключ, serial
* фио (name): varchar(100)
* идентификатор должности (id_position): внешний ключ, integer
* идентификатор адреса (id_address): внешний ключ, integer


#### Структурные подразделения (Structural Units):

* ид подразделения (id_units): первичный ключ, serial
* фио (name): varchar(100)


#### Должности (Positions):

* ид должност (id_position): первичный ключ, serial
* фио (name): varchar(100)


#### Проекты (Projects):

* ид проекта  (id_projects): первичный ключ, serial
* фио (name): varchar(100)


#### Адреса (Unit Address):

* ид адресса (id_full_address): первичный ключ, serial
* город (city): varchar(100)


#### Типы подразделений (Unit Types):

* ид типа подраздления  (id_type): первичный ключ, serial
* фио (name): varchar(100)

#### Типы подразделений (Unit Types):

* ид должности (id_position): внешний ключ, serial
* фио (name): varchar(100)
* оклад (salary) INTEGER,       (salary вместо money)
