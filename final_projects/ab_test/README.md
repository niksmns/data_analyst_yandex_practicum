# Анализ проведения и оценка результатов A/B-тестирования

## Описание проекта

В распоряжении есть датасет с действиями пользователей, техническое задание и несколько вспомогательных датасетов.

- Оценить корректность проведения теста.
- Проанализировать результаты теста.

Чтобы оценить корректность проведения теста, нужно проверить:

- пересечение тестовой аудитории с конкурирующим тестом;
- совпадение теста и маркетинговых событий, другие проблемы временных границ теста.

**`Nbviewer:`** 

[![nbviewer](https://img.shields.io/badge/VIEW-nbviewer-orange)](https://nbviewer.org/github/niksmns/data_analyst_yandex_practicum/blob/main/final_projects/ab_test/5e31a726-9723-4a87-b42e-5d2f8291020d.ipynb)

**`Предоставленные данные:`**

* календарь маркетинговых событий на 2020 год
* все пользователи, зарегистрировавшиеся в интернет-магазине в период с 7 по 21 декабря 2020 года
* все события новых пользователей в период с 7 декабря 2020 по 4 января 2021 года
* таблица участников тестов

**`Цели исследования:`** 
* провести оценку результатов A/B-теста

**`Используемые библиотеки:`**
* pandas
* matplotlib
* numpy
* scipy
* datetime
* plotly
