# Cнижение производственных расходов металлургического предприятия.

## Описание проекта
При выплавке стали варируется много параметров, которые вляют на конечную температуру. С целью снижения расходов требуется построить модель, которая бы предсказывала конечную температуру в ковше по доступным параметрам плавки. 

## Инструменты
Pandas, Numpy, Seaborn, lightGBM, Linear Regression

## Выводы
- Лучшая модель машинного обучения - lightGBM определяет определяет температуру с требуемой по заданию точностью - качество MAE равно 6.0, что ниже требуемых 6.8 и лучше константных 8.0.
- Коэффициент R2 не очень высок - 0.37, что показывает наличие резервов для улучшения модели.
