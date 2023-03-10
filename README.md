# Поиск мошенников через данные
## Проект направлен на анализ "условной" базы клиентов продукта финтеха
## В работе использован следующий стек:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## Применялись следующие подходы:
+ Join таблиц
+ python функции

## В ходе проекта мной было сделано:
+ Написан скрипт для поиска "связанных" между собой строк в датафрейме
+ Произведена проверка качества данных (пропущенные значения, количество строк)
+ Предобработка данных в датафрейме (очистка от дупликатов и лишних значений)
+ Формирование таблиц по исходным условиям

#### Результат работы: функция для поиска клиентов, пытающихся сформировать несколько учетных записей в одном сервисе, используя частично похжие данные. Скрипт позволяет определять на стадии появления значения в БД подозрительных личностей для принятия дальнейших действий. Также выполнено условие поставленного ТЗ: сформированы две таблицы клиентов, с наибольшим количеством ключевых действий. Эта информация позволит, к примеру, предложить наиболее активным клиентам особые условия пользования или, наоборот, выявить мошенников

Ознакомиться с файлом решения тут:
[Cyber_safe](Find_the_thief.ipynb)
--------------------
