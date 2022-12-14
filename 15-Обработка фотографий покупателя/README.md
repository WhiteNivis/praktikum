# [Определение возраста покупателей](https://github.com/WhiteNivis/praktikum/tree/main/15-Обработка%20фотографий%20покупателя)

Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:

 - анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
 - контролировать добросовестность кассиров при продаже алкоголя.
 
Требуется построить модель, которая по фотографии определит приблизительный возраст человека.

Цель

Определить возраст по фотографии.

Задачи

 - исследовать данные;
 - добавить аугментации при необходимости;
 - достигнуть показателя метрики 'mae' < 8.
 
Файлы

 - labels.csv - данные о возрасте;
 - final_files - папка с фотографиями.
 
Целевой признак

real_age — возраст

## Общий вывод

В качестве основы для модели предсказания возраста использовалась предобученная модель ResNet50. Достигнутые показатели:

 - train: loss: 31.0102 mae: 4.3066
 - test: loss: 80.5638 mae: 6.7031
 
Основными целями разработки модели были:

1) анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы

2) контролировать добросовестность кассиров при продаже алкоголя.

Уровень 'mae' в 7 лет не обеспечит должного качества для цели №2, рекомендуется использовать модель только для цели №1.

