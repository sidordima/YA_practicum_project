# Прогнозирование спроса на такси

## Цель

Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Построим модель для такого предсказания.
Значение метрики RMSE на тестовой выборке должно быть не больше 48. 

## Вывод

Полученное значение RMSE модели lightGBM на тестовой выборке соотвествует требованию задания и составляет 43.

## Стек

*pandas*, *statsmodels.tsa.seasonal*, *matplotlib*, *sklearn*, *math*