﻿# technicalSpecification
Тестовое задание было указано в файле: Тестовое Python.docx

Superuser:
    login: root
    password: root

Database:
    'NAME': 'dbtechnicalspecification',
        'ENGINE': 'django.db.backends.mysql',
        'USER': 'Drovosyaka',
        'PASSWORD': 'ZeusLucky13',
        'HOST': 'localhost'

MyDataBaseBackup:
    technicalSpecification->MyDataBaseBackup

Для наглядной демонстрации вывода пагинированного списка в API, было установлен размер 2, его можно в любой момент 
изменить на необходимое число в apiTechnicalSpecification/views.py в классе EquipmentPagination, изменив page_size

В ТЗ небыло предусмотрено добавления записей в "Тип оборудования", но запись можно  добавить по url адресу: 
http://127.0.0.1:8000/api/equipment-type/

По адресу: http://127.0.0.1:8000/ находится основной шаблон приложения, с реализацией:
* Просмотра записей
* Добавления записи
* Редактирования записи
* Удаления записи
