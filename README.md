# Домашнее задание к занятию "`Базы данных`" - `Dima Kolb`

## Задание 1

[таблицы](png/2.png)

#### 1. Таблица “дата найма”:
* id_name
* date


#### 2. Таблица “подразделения”:
* id_units
* id_position
* id_name


#### 3. Таблица “структурные подразделения”:
* id_structural_units
* id_units
* id_name


#### 4. Таблица “тип подразделения”:
* id_type
* id_units
* id_name


#### 5. Таблица “должность”:
* id_position
* id_name


#### 6. Таблица “оклад”:
* id_position
* money
* id_name

#### 7. Таблица "проект":
* id_projects
* id_position
* id_name

#### 8. Таблица "адресс филиала":
* id_address
* id_name

----

id (projects, structural units, address, type): int (первичный ключ)

id_name: int (вторичный ключ)

date: date

money: numeric

