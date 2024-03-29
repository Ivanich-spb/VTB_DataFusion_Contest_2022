# VTB_DataFusion_Contest_2022_PublicSolution

Публичное решение для задач Matching & Puzzle [VTB DataFusion Contest 2022](https://ods.ai/tracks/data-fusion-2022-competitions)
### Authors:
 - Иван Александров https://github.com/Ivanich-spb
 - Петр Михайлов https://github.com/PeMikj
 
### Results:
- 2-ое место в номинации Companion (лучшее публичное решение)
- 3-е место в номинации Insight
- 4-ое место в задаче Education
- 9-ое место в задаче Puzzle
- 12-ое место в задаче Matching
 
### Description:
Необходимо решить Matching задачу, используя данные транзакций клиентов банка и кликстрима интернет-пользователей компании "Ростелеком".
Решение сдается в формате контейнеров с кодом.
[Данные для задачи](https://ods.ai/competitions/data-fusion2022-main-challenge/Dataset)

Решение протестиовано: на Public Leaderboard позволяет зайти в top-20 по обеим задачам(на 01.05.2022). </br>
- R1: более 0.26 (Matching)
- R1: более 0.040 (Puzzle) </br>

Фичи представлены самые простые, чтобы продемонстрировать подходы к решению и направления для экспериментов.

### Requirements:
- Протестировано на бесплатных ресурсах платформ Kaggle & GoogleColab
- Для запуска локально: 16Gb Ram, GPU(optional)

### Key Features:
- Функции для обнаружения и удаления выбросов
- Функция генерации "SMART" негативов
- Отсечение признаков по "feature importance"
- Обучение CatBoost Ranker с ранжирующим лоссом
- Локальная валидация </br>
