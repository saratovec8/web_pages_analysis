# web_pages_analysis
Kaggle соревнование https://www.kaggle.com/c/anomaly-detection-competition-ml1-ts-fall-2020
Проект выполнен совместно с Булатом Валиахметовым: https://github.com/bulatral42.

Основная идея: внутри группы у не_выбросов ближайшие соседи расположены ближе, чем у выбросов. Для этого измеряем различными способами расстояния между веб-страницами. Использованы: bag-of-words и cosine расстояния над заголовками, tf-idf и doc2vec преобразованиями страниц.

Итоговый f1-score на Private Leaderboard на момент окончания соревнования: 0.711711 (топ-6)
