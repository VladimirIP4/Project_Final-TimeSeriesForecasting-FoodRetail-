# Прогнозирование спроса на основе временных рядов

## Оглавление  
[Описание проекта](.README.md#Описание-проекта)    
[Краткая информация о данных](.README.md#Краткая-информация-о-данных)  
[Этапы работы](.README.md#Этапы-работы)  
[Результаты](.README.md#Результат)    
[Выводы](.README.md#Выводы) 

### Описание проекта    
Мы будем использовать реальные данные о продажах сети магазинов Favorita из Эквадора, чтобы построить модель для прогнозирования продаж. 

:arrow_up:[к оглавлению](_)


### Краткая информация о данных
Обучающие данные (train.csv), включающие временные ряды признаков store_nbr, family и onpromotion, а также целевой признак sales.
Дополнительные данные о праздничных днях (holidays_events.csv).
  
:arrow_up:[к оглавлению](.README.md#Оглавление)


### Этапы работы 
1. Загрузка и ознакомление с данными;
2. Обработка и очистка данных;
3. Применение статистические методы для анализа данных;
4. Применение инструменты визуализации;
5. Применение машинного обучения и глубокого обучения;
6. Заключение.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
Подготовили данные и обучили на этих данных модели машинного обучения и глубокого обучения Naive (Naive, Seasonal Naive, Seasonal Window Average, Window Average), ARIMA, Scikit-learn (Random Forest, Extra Trees), LightGBM, XGBoost, Prophet, GRU, LSTM, N-BEATS, DeepAR, - среди которых лучшие прогнозы по 4 из 5 семейств товаров продемонстрировала модель Prophet.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
В данном проекте удалось применить на практике:
- раведывательный анализ данных (EDA)
- визуализацию данных
- проведение статистических тестов
- создание моделей машинного обучения
- оценку результатов предсказаний
- написание кода на Python

:arrow_up:[к оглавлению](.README.md#Оглавление)
