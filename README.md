В этой работе мы посмотрим на то, как работают самые простые модели для рекомендаций. Как правило, они не 
требуют построения специальных моделей, но даже так оказываются полезны в качестве бейзлайна. Попробуем сделать 
предсказания с помощью EASE. Это тоже довольно простой подход, но не стоит забывать, что сложные модели могут оказаться 
не лучшим выбором в условиях большого количества данных. Посчитаем метрики, построим графики и подумаем, насколько хорошо 
эти модели вообще решают поставленную задачу Мы будем работать с датасетом по рекомендации фильмов от Kion MTS, который был
дан для соревнования. Сперва нужно его предобработать.


Датасет необходимо скачать: https://ods.ai/competitions/competition-recsys-21/data Оттуда нужны файлы interactions.csv и items.csv
