# ControlWorkC-
1. Создаём два массива типа string, Words и Array
2. Массив array будет равен длинне words.  (string[] array = new string[words.Length])
3. Создаём переменную int maxNumOfChar и присваиваем ей значение 3 (во избежание магических чисел в коде).
4. Создаём переменную Count, которая будет указывать на ячейку в массиве array и присваиваем ей значение 0.
5. Создаём метод ValidateStrSymbol типа void, принимающий в качестве аргументов 2 массива , исходный с данными(words) и тот, в который будут записанны строки длинна которых меньше 3х символов (array).
6. В теле метода создаём цикл for , который будет пробегать по элементам массива words
7. В теле цикла создаём условие if (words[i].Length <= maxNumOfChar)
8. Если условие выполняется, записываем значение элемента i( массива  words), в ячейку [count] ( массива array). Повышаем значение count на +1.
9. Если условие не выполняется, переходим на следующую итерацию.


Так же у нас есть метод PrintArray принимающий в качестве аргументов массив типа string, выводящий элементы переданного в него массива в консоль, с отступом 5 знаков.
