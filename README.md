# Прогнозирование спроса на основе временных рядов в продуктовом ритейле

## Описание проекта    
На основе временных рядов продаж товаров необходимо построить прогноз на следующие 14 дней. Планируется сравнить несколько методов прогнозирования и использовать наилучший для прогнозирования продаж каждого из 180 товаров.

## Краткая информация о данных
##### /plotly
Большинство графиков сделаны с помощью библиотеки plotly и сохранены в соответствующей папке.

##### /models
Модели в формате pickle для каждого товара, обученные и сохраненные по итогам работы.

##### /data
В наличии датасет с продажами 180 товаров в одном магазине в течение 1 года. А именно для каждого товара:
- захэшированное id товара
- дата
- флаг наличия промо
- число проданных товаров всего
- число проданных товаров с признаком промо
- продажи всего в РУБ
- продажи с признаком промо в РУБ

## Этапы работы:
### 1. Анализ и обработка данных:
##### 1.1 Обработка и очистка данных.
##### 1.2 Пропуски в данных.
##### 1.3 Анализ по продажам в штуках, рублях.
### 2. Проверка способов решения:
##### 2.1 Выбираем 3 товара для сравнения разных моделей.
##### 2.2 Naive, SeasonalNaive, ExponentialSmoothing, SeasonalWindowAverage, AutoARIMA.
##### 2.3 Machine Learning — Linear Regression, XGBoost, LGBM.
##### 2.4 Сравнение прогнозов моделей.
##### 2.5 Выводы.
### 3. Основное решение:
##### 3.1 Создаем датасеты для обучения модели для каждого товара.
##### 3.2 Обучаем модели и проверяем результат на графике + метрика WAPE.
##### 3.3 Оптимизация гиперпараметров.
##### 3.4 Работа с фичами.
##### 3.5 Сериализация и сохранение моделей.


## Результаты:  
Исследованы и подготовлены данные. На них проверено несколько методов прогнозирования - Naive, SeasonalNaive, ExponentialSmoothing, SeasonalWindowAverage, AutoARIMA, Linear Regression, XGBoost, LGBM. Выбрана лучшая модель - LGBM. Разарботаны датасеты с новыми признаками для каждого товара и обучено 180 моделей. Средний показатель WAPE - 10.

## Выводы:  
В данном проекте удалось применить на практике:
- раведывательный анализ данных (EDA)
- визуализацию данных
- проведение статистических тестов
- создание моделей машинного обучения
- оценку результатов предсказаний
- написание кода на Python
