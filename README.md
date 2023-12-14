coursework_5_hh_sql

Проект реализован для получения вакансий 10 работодателей с сайта HeadHunter по API, используя библиотеку requests и последующим сохранением их в базу данных, используя библиотеку psycopg2. 

Используемая СУБД - PostgreSQL.

Запустить программу необходимо в main.py, указать название БД для сохранения в нее информации, далее следовать инструкции.
После сохранения данных пользователь имеет возможность выбрать следующие критерии отбора вакансий:
получить список всех компаний и количество вакансий у каждой компании,
получить список всех вакансий с указанием названия компании, названия вакансии и зарплаты и ссылки на вакансию,
получить среднюю зарплату по вакансиям,
получить список всех вакансий, у которых зарплата выше средней по всем вакансиям,
получить список всех вакансий, в названии которых содержатся переданные в метод слова
