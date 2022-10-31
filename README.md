# Учебные проекты 

Учебные проекты в рамках курса ["Специалист по Data Science плюс"](https://praktikum.yandex.ru/profile/data-scientist-plus/)  в Яндекс.Практикум.  
  
| Название проекта | Задачи проекта | Описание | Навыки и инструменты |
| ----------------- | ----------------- | ----------------- | --- |
| [15-Обработка фотографий покупателя]() | Определение возраста по фотографии | Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Строится модель, которая по фотографии определит приблизительный возраст человека. | Python, Keras |   
| [14-Обучение модели классификации комментариев]() | Определение токсичности комментариев | Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. | Python, Pandas, BERT, nltk, tf-idf |   
| [13-Прогнозирование количества заказов такси на следующий час]() | Разработка системы предсказания количества заказов |  Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Строится модель для такого предсказания. | Python, Pandas, Scikit-learn, statsmodels | 
| [12-Разработка системы предупреждения аварий на каршеринге]() | Построить систему предупреждения об аварии клиентам каршеринга | На основе исторических данных из базы данных выявить причины возникновения аварий и создать алерт (напоминание) о безопасном вождении. | SQL, Pandas, Scikit-learn, PostgreSQL, SQLalchemy | 
| [11-Прогнозирование темпаратуры звезды]() | Определить температуру на поверхности звезды | На основе косвенных данных построить модель оценки температуры на поверхности звезды | Python, Pandas, Pytorch, Skorch |  
| [10-Построение модели определения стоимости автомобиля]() | Разработка системы рекомендации стоимости автомобиля на основе его описания | Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля. | Python, Pandas, CatBoost, LightGBM |  
| [09-Защита данных клиентов страховой компании]() | Разработка модели анонимизации персональных данных |  Необходимо защитить данные клиентов страховой компании разработав такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.  | Python, NumPy, Scikit-learn | 
| [08-Прогнозирование стоимости жилья в жилом массиве]() | Определить медианную стоимость квартиры |  Сервис по продаже квартир закал разработку модели по прогнозированию стоимости квартиры  | Python, Pandas, Matplotlib, Seaborn, Spark | 
| [07-Система прогнозирования продажи отелей]() | Спрогнозировать кто из клиентов откажется от брони | Строится модель прогнозирования отказа от брони клиента. В качестве метрики предлагается использовать величину выручки которая получится после внедрения модели машинного обучения. | Python, Pandas, Matplotlib, Seaborn, NumPy, Scikit-learn, исследовательский анализ данных |   
| [06-Определение наиболее выгодного региона нефтедобычи]() | На основе данных геологоразведки выбрать район добычи нефти | Предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Требуется построить модель для определения региона, где добыча принесёт наибольшую прибыль.  | Python, Pandas, Matplotlib, Seaborn, Scikit-learn, бутстреп |   
| [05-Прогнозирование оттока клиентов Банка]() | На основе данных из банка определить клиента, который может уйти | Из банка стали уходить клиенты. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. | Python, Pandas, Matplotlib, Seaborn, Scikit-learn |   
| [04-Классификаиция клиентов телеком компании]() | На основе данных предложить клиенту тариф | Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Требуется построить систему, способную проанализировать поведение клиентов и предложить пользователям один из новых тарифов. | Python, Pandas, Matplotlib, Seaborn, Scikit-learn |    
| [03-Определение выгодного тарифа для телеком компании]() | На основе данных клиентов оператора сотовой связи выполнить анализ поведения клиентов и поиск оптимального тарифа | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов. | Python, Pandas, NumPy, SciPy, Matplotlib, Seaborn, описательная статистика, проверка статистических гипотез | 
| [02-Исследование рынка российского кинопроката]() | Выполнить исследование рынка российского кинопроката | Изучить рынок российского кинопроката и выявить текущие тренды. Сделать аналих насколько фильмы, которые получили государственную поддержку, интересны зрителю. | Python, Pandas, Matplotlib |  
| [01-Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости]() | Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания. | Python, Pandas, Matplotlib, исследовательский анализ данных, визуализация данных, предобработка данных |  

Репозиторий содержит значимые и крупные учебные проекты.

