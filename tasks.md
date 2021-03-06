# Задачи, которые необходимо сдать за семестр

1. Задача из списка подготовительная «С клавиатуры вводятся 4 числа — координаты двух точек...»
2. Задача из списка на последовательности («С клавиатуры вводится последовательность чисел неизвестной длины...»)
3. Задача 2 с модификацией: последовательность чисел вводится в аргументах командной строки.
4. Задача на указатели: написать функцию, которая определяет минимум и максимум последовательности чисел и записывает их по указателю в переменные, объявленные в функции `main`.
5. Задача 2 с модификацией: последовательность чисел находится в файле, имя которого передаётся в аргументе командной строки.
6. Задача из списка на массивы («Написать функцию, получающую в качестве аргументов массив...»)
7. Реализовать 4 алгоритма сортировки по возрастанию массивов вещественных чисел (пузырьковая, сортировка слияниями, quicksort, пирамидальная) и программу, сравнивающую время работы этих алгоритмов для следующих видов входных данных:
- массив, отсортированный по возрастанию;
- массив, отсортированный по убыванию;
- массив, заполненный случайными числами.
Программа должна выводить время работы для каждого алгоритма сортировки, для каждого вида входных данных, для размеров N, 2N и 4N.
8. Задача 6 с модификацией: дополнительно вывести отсортированную последовательность. 
9. Контрольная работа по списку («В файлах указаны последовательности неизвестной длины...»).
10. Самостоятельная работа на занятии 27 ноября, сдаётся в виде исходного кода в конце занятия.
11. Самостоятельная работа на занятии 4 декабря, сдаётся в виде исходного кода в конце занятия.
12. Самостоятельная работа на занятии 11 декабря, сдаётся в виде исходного кода в конце занятия.

Задача 5 может быть засчитана и за задачи 2 и 3.

Задача 8 может быть засчитана и за задачу 6.

По итогам контрольной работы и трёх самостоятельных работ на зачётах может потребоваться дополнительно сдать ещё 1-2 «штрафные» задачи.

# Требования к программам

Исходный код по задачам принимается в корректно оформленном, удобном для чтения виде, минимальные требования (может оказаться недостаточно):

- каждая команда — на отдельной строке;
- операторы отделены от операндов пробелами за исключением мультипликативных и унарных операций и скобок, но включая запятую (можно: `a = (a + b*c)/4;`, можно `a++;`, нельзя `a=a+1;`);
- тело цикла и условного оператора обязательно должно быть блоком (нельзя: `if (a) b = c;`);
- внутри блока (фигурных скобок) отступ увеличивается на 2-4 пробела или один символ табуляции (одно и то же значение для всего кода);
- первая команда блока пишется на новой строке (нельзя: `{ x = 1; }`);
- определения функций должны отделяться двумя пустыми строками, прототипы можно не отделять пустыми строками.

Программа должна быть написана самостоятельно, студент должен разбираться в коде и уметь внести правки на месте по замечаниям.

Код должен собираться компилятором в дисплейных классах без ошибок и предупреждений. Задачи должны корректно завершать работу для любых входных и выходных данных и освобождать использованную память во всех случаях. Допускается сообщение об ошибке, выводимое программой при некорректных входных данных. Не допускается аварийное завершение («падение») программы с ошибкой сегментации, исключением в операции с плавающей точкой и т.п.
