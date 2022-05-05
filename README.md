# VTB_DataFusion_Contest_2022_PublicSolution

Публичное решение для задач Matching & Puzzle [VTB DataFusion Contest 2022](https://ods.ai/tracks/data-fusion-2022-competitions)

### Description:
Необходимо решить Matching задачу, используя данные транзакций клиентов банка и кликстрима интернет-пользователей компании "Ростелеком".
Решение сдается в формате контейнеров с кодом.
[Данные для задачи](https://ods.ai/competitions/data-fusion2022-main-challenge/Dataset)

Решение протестиовано: на Public Leaderboard позволяет зайти в top-20 по обеим задачам(на 01.05.2022). </br>
Фичи представлены самые простые, чтобы продемонстрировать подходы к решению и направления для экспериментов.

### Requirements:
- Протестировано на бесплатных ресурсах платформ Kaggle & GoogleColab
- Для запуска локально: 16Gb Ram, GPU(optional)

### Key Features:
- Функции для обнаружения и удаления выбросов
- Функция генерации "SMART" негативов
- Отсечение признаков по 'feature importance'
- Обучение CatBoost Ranker с ранжирующим лоссом
- Локальная валидация </br>

*При скачивании с Kaggle, к сожалению не сохраняются outputs ноутбука
