# Исследование объявлений о продаже квартир

В нашем распоряжении данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Необходимо научиться определять рыночную стоимость объектов недвижимости. Для этого нужно провести исследовательский анализ данных и установить параметры, влияющие на цену объектов. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта и других объектов — эти данные автоматически получены из геосервисов. Количество парков и водоёмов также заполняется без участия пользователя.
# Что было изучено
## Первые графики и выводы  
- Применение сводных таблиц  
- Гистограмма  
- Распределения  
- Диаграмма размаха  

## Изучение срезов данных  
- Метод query()  
- Работа с датой и временем  
- Построение графиков методом plot()  
- Бритва Оккама  

## Работа с несколькими источниками данных  
- Срез данных на основе внешних объектов  
- Добавление новых столбцов в датафрейм  
- Добавление данных из других датафреймов  
- Переименование столбцов  
- Объединение таблиц  

## Взаимосвязь данных  
- Диаграмма рассеяния  
- Корреляция переменных  
- Матрица диаграмм рассеяния  

## Валидация результатов  
- Укрупнение групп  
- Разбиение данных по группам  
