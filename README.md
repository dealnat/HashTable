# HashTable

В этом проекте была реализована хеш таблица.
Проблема коллизий решена методом цепочек.
Класс хеш таблицы реализован с шаблоном, поэтому можно создать хеш таблицу из любого базового типа.
Хеш функция приводит ключ к строке, разбивает на символы и суммирует их ASCII значения. Чтоб не выйти за пределы массива полученое значение берется по модулю размера таблицы.
