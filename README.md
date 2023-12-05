# <center> Проект: Анализ резюме из HeadHunter

#### <center> Проект включает в себя 4 раздела:

## Оглавление
1. [Исследование структуры данных](#Исследование-структуры-данных)
2. [Преобразование-данных](#Преобразование-данных)
3. [Разведывательный-анализ-и-визуализация](#Разведывательный-анализ-и-визуализация)
4. [Очистка-данных](#Очистка-данных)

## Исследование структуры данных
Здесь мы смотрим: 
- правильно ли загрузились наши данные
- из каких столбцов состоят данные, какого типа столбцы

## Преобразование данных
Этот этап самый сложный, ведь наши данные очень «сырые»: признаки представлены в неудобном для анализа и очистки формате.

Например, столбец «Пол/возраст» содержит информацию и о поле, и о возрасте, и о дате рождения. Желаемая заработная плата представлена в виде текста с указанием валюты, в которой она исчисляется, и так далее…

Всё это не позволяет нам визуально оценить зависимости в данных: построить гистограмму распределения зарплаты и возраста, столбчатую диаграмму зарплаты по уровню образования и многое другое. Более того, мы не можем в таком виде заполнить пропущенные значения числовыми константами или найти выбросы. Иными словами, нам необходимо преобразовать данные, что позволит грамотно работать с ними.

## Разведывательный анализ и визуализация
В данном шаге мы визуализируем некоторые зависимости в данных, строя множество графиков

Тут важна аналитика и здравый смысл, благодаря которым мы находим аномальные значения, к примеру возраст в 100 лет, или желаемая зарплата в 25,6 миллионов.
После визуализации мы будем иметь представления о выбросах, которые в последствии и уберём.

## Очистка данных
И заключительным этапом этого проекта будет избавление от аномальных значений (выбросов), после их удаления модель машинного обучения будет работать более точно.

Важность этого этапа можно понять из поговорки: "Мусор на входе - мусор на выходе", что означает: нужно максимально "причёсывать" данные, чтобы результат был стоящим.

## Данные

* https://lms-cdn.skillfactory.ru/assets/courseware/v1/15abf80f45a2f3e93c3274101b451c67/asset-v1:SkillFactory+DSPR-2.0+14JULY2021+type@asset+block/ExchangeRates.zip
* https://drive.google.com/file/d/1Kb78mAWYKcYlellTGhIjPI-bCcKbGuTn/view?usp=sharing

## Используемые зависимости
* Python (3.9):
    * [numpy (1.20.3)](https://numpy.org)
    * [pandas (1.3.4)](https://pandas.pydata.org)
    * [matplotlib (3.4.3)](https://matplotlib.org)
    * [seaborn (0.11.2)](https://seaborn.pydata.org)

## Установка проекта
```
    git clone https://github.com/ArtemyiMelehin/Head-Hunter-Project
```

## Использование
Вся информация о работе представлена в jupyter-ноутбуке data_cleaning_example.ipynb.

## Авторы

* [Мелехин Артемий](https://vk.com/rationality1379)

## Выводы

Я выполнил первую часть любого проекта основаного на больших данных, тем самым заложил хорошую почву для дальнейшего машинного обучения.