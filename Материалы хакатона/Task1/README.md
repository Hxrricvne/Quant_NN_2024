## Задача 1
Решение задачи сведено к модели QUBO. Была получена матрица коэффициентов Q с учетом ограничений для решения поставленных задач оптимизации рисков и доходности инвестиционного портфеля. Использовался семплер для отжига из библиотеки neal.

## Пример использования
--- Загружаем файл csv с ценами акций с произвольным временным интервалом. 
--- В качестве результата выполнения алгоритма получаем вектор весов, показывающий сколько и каких акций нужно приобрести в портфель, а также среднюю доходность портфеля, стоимость портфеля в последний день и риск.

## Полученные результаты
В ходе обработки исходного датасета была получена доходность портфеля ~ 0.00045 с риском равным 0.192. 
