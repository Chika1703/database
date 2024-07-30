# Домашнее задание к занятию "`GIT`" - `Dima Kolb`

### Задание 1

####Сотрудники (Employees):

1. идентификатор (id): первичный ключ, serial
2. фио (name): varchar(100)
3. идентификатор должности (id_position): внешний ключ, integer
4. идентификатор адреса (id_address): внешний ключ, integer


####Структурные подразделения (Structural Units):

1. идентификатор (id_units): первичный ключ, serial
2. название (name): varchar(100)


####Должности (Positions):

1. идентификатор (id_position): первичный ключ, serial
2. название (name): varchar(100)


####Проекты (Projects):

1. идентификатор (id_projects): первичный ключ, serial
2. название (name): varchar(100)


####Адреса (Unit Address):

1. идентификатор (id_full_address): первичный ключ, serial
2. город (city): varchar(100)


####Типы подразделений (Unit Types):

1. идентификатор (id_type): первичный ключ, serial
2. название (name): varchar(100)
