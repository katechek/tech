# Технологии программирования #
# Задание #
Реализуйте на Java простейшую программу, которая будет считывать из файла числа, а далее отдельными функциями искать среди этих чисел минимальное число, максимальное число, считать их общую сумму и произведение.

Функции должны называться, соответственно min (минимальное число), max (максимальное число), sum (сумма всех чисел), mult (произведение всех чисел).

Числа в файле записаны в одной строке, друг от друга отделены пробелами. В файле есть минимум одно число. Максимально возможное количество чисел в файле - 1 млн.

Для этой программы подготовьте тесты:
1) проверяющие корректность работы функций поиска минимума и максимума
2) проверяющие корректность работы функций сложения и умножения
3) проверяющие скорость работы программы при увеличении размера входного файла (при увеличении количества чисел в файле)
Необходимо настроить CI-систему для проекта

Тестирование выполнено с помощью Maven.
https://t.me/Ftsj26 - ссылка на телеграм-бота
   
   ![Java CI with Maven](https://github.com/katechek/Programming-technology/actions/workflows/check2.yml/badge.svg)


# Зависимость скорости выполнения функции min() от количества символов во входном файле #
С увеличением количества элементов во входном файле увеличивается время работы программы, так как требуется проверить больше чисел. Кроме того, т.к. программа реализована через List, то для доступа к нужному элементу может требоваться больше времени
![image](https://github.com/katechek/Programming-technology/assets/62990618/d3925bab-6207-48c3-ad98-ca107aaf8963)
