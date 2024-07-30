# Домашнее задание к занятию "`Базы данных`" - `Dima Kolb`

## Задание 1

[таблицы](png/1.png)


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
* оклад (money) INTEGER

-----


structural_units:
Данные: Информация о структурных подразделениях
units_id (INT), name (INT)

units:
Данные: Детали отдельных единиц или членов.
id (INT), position_id (INT), name (INT).

projects:
Данные: Информация о проектах.
id (INT), position_id (INT).

unit_types:
Данные: Типы подразделений
id_type (INT), name (TEXT).

position:
Данные: должности
id_position (INT), name (INT)

full_address:
Данные: Адресная информация.
id_address (INT), id_city (INT), full_address (TEXT)

workers:
фио (TEXT)? id_name (INT), date (date)

и т.д
