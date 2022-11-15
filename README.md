# URSip_Liquid_and_Oil


![Screen Shot](Demo.gif)

## Описание проекта

Небольшой парсер, конвертирующий файл excel в базу данных SQLite3

## Стек технологий 

В ходе создания проекта применялись различные инстументы и технологии. Они представлены ниже:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

## Инструкция по установке 

1. Клонируете репозиторий

```sh
git clone https://github.com/XanderMoroz/URSip_Liquid_and_Oil.git
```
2. В файле main.py укажите имена базы данных, таблицы и файла excel
```sh
sqlite3.connect("dbName.db")    # Создайте базу данных самостоятельно с помощью sqlite3.
dbName = "dbName"               # Установите имя базы данных в качестве переменной функции.
tableName = "testName"          # Установите имя таблицы базы данных.
excelName = "Задание бек.xlsx"  # Установите имя excel файла.
```
3. Запустите скрипт
```sh
test = ExcelToSqlite(dbName)          # Создание экземпляра класса;
test.ExcelToDb(tableName, excelName)  # Передача названий таблицы БД и файла Excel;
test.Query(tableName)                 # Вывод преобразованной таблицы в консоль.
```
4. Наслаждаетесь результатом)

### Лицензия

Лицензия не требуется. Проект может быль использован без ограничений. 

### Авторы

* [XanderMoroz](https://https://github.com/XanderMoroz/) - *Все работы*
