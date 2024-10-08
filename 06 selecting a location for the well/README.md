# Определение наиболее выгодного региона нефтедобычи
## Данные 
Данные геологоразведки трёх регионов, данные по каждому региону в отдельных .csv таблицах
  - id — уникальный идентификатор скважины;
  - f0, f1, f2 — три признака точек (неважно, что они означают, но сами признаки значимы);
  - product — объём запасов в скважине (тыс. баррелей).
## Задача проекта
Для исследования предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Необходимо построить модель для определения региона, где добыча принесёт наибольшую прибыль. 
## Используемые библиотеки
  - pandas
  - scikit-learn
  - matplotlib
  - numpy
  - seaborn
  - shap
  - pink
  - ydata_profiling
## Вывод
Была подобрана лучшая модель машинного обучения для решения данной задачи, так же был проведен расчет прибыли и рисков для каждого региона и выбран один полностью удовлетворяющий условию заказчика.
