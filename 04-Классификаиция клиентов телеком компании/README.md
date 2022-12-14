# [Разработка рекомендательной модели тарифов сотовой связи](https://github.com/WhiteNivis/praktikum/tree/main/04-Классификаиция%20клиентов%20телеком%20компании)

Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Компания хочет построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».
В нашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. 

<font color='green'>Цель</font>

Нужно построить модель, которая выберет подходящий клиенту тариф. Основная метрика эффективности - `accuracy`.

<font color='green'>Задачи</font>

- изучить данные;
- разделить исходные данные на обучающую, валидационную и тестовую выборки;
- исследовать качество следующих моделей:
  
      1) Решающее дерево
      2) Cлучайный лес
      3) Логистическая регрессия
  
- проверить качество модели на тестовой выборке;
- проверить модель на адекватность сравнив с искусственной.

<font color='green'>Файлы</font>

- `users_behavior.csv`

<font color='green'>Столбцы</font>

- `сalls` — количество звонков,
- `minutes` — суммарная длительность звонков в минутах,
- `messages` — количество sms-сообщений,
- `mb_used` — израсходованный интернет-трафик в Мб,
- `is_ultra` — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

<font color='green'>Содержание</font>

## Общий вывод

Рабочей моделью для выбора подходящего клиенту тарифа признана модель `"Cлучайный лес"` со следующими параметрами:

	RandomForestClassifier(max_depth=5, n_estimators=63, random_state=12345)

`Accuracy` модели:

- на валидационной выборке:   0.8242612752721618
- на тестовой выборке:        0.80248833592535

Модель признана приемлемой.

Из-за несбалансированности классов введены дополнительные метрики: `precision` и `recall`. Их покаказатели для тестовой выборки:

    Precision:  0.807
    Recall:     0.467        
