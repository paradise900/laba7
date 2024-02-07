# Lab-7
Лабораторная работа №7

Использование NumPy и MatPlotLib

**Задание**

1. Библиотека NumPy имеет очень быстрые алгоритмы работы с массивами. Убедитесь в этом, сравнив время выполнения операции поэлементного перемножения стандартных списков
и массивов NumPy (```numpy.array```). Для каждого случая создайте два массива в 1 миллион элементов, заполненных случайными значениями чисел, и перемножьте их (в NumPy 
для этого служит функция ```numpy.multiply()```). Чтобы замерить время выполнения, воспользуйтесь функцией ```perf_counter``` из библиотеки ```time```.

2. Подгрузите один из двух приложенных файлов ```data1.csv``` и ```data2.csv```. Выделите данные из столбцов, указанных в вашем варианте и сгенерируйте из них график
(для ```data1.csv```) или гистограмму (для ```data2.csv```). В первом случае необходимо вывести два графика, наложенные друг на друга, а также график корреляции.
Во втором случае: гистограмму, нормализованную гистограмму и среднеквадратичное отклонение. Количество столбцов в гистограмме произвольное, но не менее 16. Каждый график должен содержать заголовок и подписи по осям.

3. Постройте трёхмерный график согласно формуле из вашего варианта. Используйте ```Axes3d```. В интервалах потребуется ```np.linspace()```.

| Вариант | Файл | Столбец(-цы) | Формулы |
| ------- | ---- | ------------ | ------- |
| 4 | data2.csv | 2 | x∈(-5;5); y∈(-5;5); z=sin(x^y) |



**Дополнительное задание**

Создайте анимированный график функции y = sin(x) при помощи ```PillowWriter```.
