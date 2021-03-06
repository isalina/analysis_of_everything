## Исследование данных авиакомпаний  

_____________________________________________________________________________
**Цель:** Произвести выгрузки и подготовку данных авиакомпаний с помощью SQL, на оснований данных определить наиболее популярные направления в августе 2018 года, а также произвести анализ популярности определенных моделей самолетов.

_____________________________________________________________________________
**Результат:** 

1. Популярность моделей самолетов связана с количество пассажирских мест в них. Нерентабельно запускать огромные Боинги для перевозки небольшого количества пассажиров. 

2.Топ-10 городов: Москва, Санкт-Петербург, Новосибирск, Красноярск, Екатеринбург, Ростов-на-Дону, Пермь, Брянск, Сочи, Ульяновск. 

Существует сильная положительная взаимосвязь среднего количества рейсов в день и численности населения в городе. Кроме того, популярны туристические и рабочие направления (Ульяновск - авиционная столица России)

_____________________________________________________________________________
**Технологии:** pandas,  numpy, seaborn, matplotlib, plotly.express

_____________________________________________________________________________
**Статус проекта:** Завершен.

_____________________________________________________________________________

### План выполнения проекта  

Шаг 1. Импорт файлов, изучение общей информации

Шаг 2. Подготовка данных

Шаг 3. Определение топ-10 городов вылета

Шаг 4. Модели самолетов и количество рейсов

Шаг 5. Города и количество рейсов. Топ 10 городов

Шаг 6. Выводы


### Описание данных: 
**Таблица `models_flights`** - результат первого запроса в SQL. Здесь содержится информация о количестве рейсов для каждой модели самолетов в сентябре 2018 года.

**Таблица `cities_flights` ** - результат третьего запроса в SQL. В нем содержатся данные о среднем количестве рейсов, которые прибывали в города за день в августе 2018 года.
