## Задание 

> Написать программу, которая из имеющего массива строк формирует массив из строк, длинна которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
## Примеры
* ["hello", "2", "world", ":-)"] -> ["2", ":-)]
* ["1234", "1567", "-2", "computer science"] -> ["-2"]
* ["Russia", "Denmark", "Kazan"] -> []

## Описание программы

1 На старте выполнения аллгоритма создаем массив со строками и пустой массив для записи результатов.

2 В первом цикле проверяем длинну строки каждого элемента массива.  

* Если длинна строки меньше или равна трем, то в пустой массив записываем найденный элемент.

3 Во втором цыкле выводим результат