# Раннее выявление инцидентов транспорта с использованием аудиозаписей переговоров


Для реализации предлагается использовать звук переговоров. Задача состоит из двух частей: оработка речи и обработка естественного языка. Более подробно [Design Doc](https://github.com/dmitrii-naumenko/Pet_SST_NLP-repo.nosync/blob/main/Design%20doc.md)

Описание файлов проекта

- notebooks/dataset_preporation.ipynb - подготовка датасетов (перевод на русский, текст в речь, разделение на ренировку и тест)
- notebooks/stt.ipynb - модели перевода речи в текст
- notebooks/* - остальные файлы решения в виде блокнотов
- data/disaster_tweets.csv - изначальный датасет с твитами и разметкой аварий
- data/dataset_1000_ru.csv - сокращенный датасет
- data/yandex_stt_valid.csv - валидационный датасет для SST модели Yandex
- data/train.csv, valid.csv, test.csv - сплитованный датасет
- data/speech - директория с аудиофайлами
