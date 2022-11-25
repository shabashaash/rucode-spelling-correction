# RuCode Spelling correction
Моё решение задачи по исправлению ошибок на RuCode6, на базе ruT5-base от сбера.
# Ссылка на веса модели на [Google Drive](https://drive.google.com/file/d/1lmT1tCbX-s3MDxMhvO1NvXbMffeXpPLp/view?usp=sharing)
# Инструкция по запуску
0. Скачать данные для исправления в виде csv файла, положить в папку ./data/ (стандартное название для файла private_test.csv)
1. Открыть блокнот
2. Установить и импортировать модули
3. Инициализировать датасет без лейблов (SCPredictDataset)
4. Инициализировать аргументы для запуска (Args)
5. Инициализировать PLModule (SCModel)
6. Запустить последовательно все ячейки в Inference
    - ИЛИ
    - Скачать веса модели вручную и положить в тоже место, где находится блокнот
    - Запустить последовательно все ячейки в Inference, кроме "Downloading checkpoint from google drive"
