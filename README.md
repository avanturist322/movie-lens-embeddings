# movie-lens-embeddings
# **Получение эмбеддингов для пользователей и фильмов из датасета MovieLens (full) c использованием нейросетевого подхода**

[Датасет](https://grouplens.org/datasets/movielens/latest/) состоит из: 27 000 000 оценок и 1 100 000 применений тегов, примененных к 58 000 фильмов 280 000 пользователями. Включает данные генома тегов с 14 миллионами оценок релевантности по 1 100 тегам. Последнее обновление 9/2018.

В первой и второй части данной работы выполнена первичная подготовка датасета **MovieLens (full)**, а также визуализация закономерностей и зависимостей данных, проведен анализ результатов.

Во второй части работы выполнено разбиение датасета на тестовую и валидационную части, реализован `DataLoader` для этих частей, написана архитектура нейронной сети на фреймворке PyTorch, а также выполнено обучение и валидация модели.

В завершающей, третьей части, произведен вывод полученных векторных представлений (эмбеддингов), а также небольшая демонстрация работы рекомендационного алгоритма.
