# Neural-Net-to-predict-house-prices
In this project i used Keras and TF to predict prices of houses

Итак, в этом проекте мы имеем некоторый файл в формате csv. И действуем по стандартному алгоритму: смотрим на наш дата-фрейм (какие там параметры есть, какие где возможно корреляции и т.п.), делаем несколько графиков. после чего преобразуем данные, что бы их можно было бы затащить в нашу будующую нейронную сетку.

Для работы с данными используем sklearn и tensorflow. Модель берём sequential (https://www.tensorflow.org/guide/keras/sequential_model - тут подробнее, когда и почему её надлежит брать). Наполняем сетку нейронами, в них используем активационную функцию relu (об активационных функциях [тут][]. Затем тренируем сетку.

После чего мы проверяем насколько она эффективна (среднячок) и пытаемся, используя её предсказать один элемент нашего дата-фрейма

[тут]: https://neerc.ifmo.ru/wiki/index.php?title=%D0%9F%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%D0%B8_%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8_%D0%BD%D0%B5%D0%B9%D1%80%D0%BE%D0%BD%D0%BD%D1%8B%D1%85_%D1%81%D0%B5%D1%82%D0%B5%D0%B9#:~:text=%D0%A4%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8E%20%D0%B0%D0%BA%D1%82%D0%B8%D0%B2%D0%B0%D1%86%D0%B8%D0%B8%20ReLU%20%D1%81%D0%BB%D0%B5%D0%B4%D1%83%D0%B5%D1%82%20%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C,%D0%BD%D0%B5%D0%B9%D1%80%D0%BE%D0%BD%D0%B0%2C%20%D0%B2%D1%80%D0%BE%D0%B4%D0%B5%20%D0%BD%D0%B5%D0%BE%D0%B3%D1%80%D0%B0%D0%BD%D0%B8%D1%87%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D0%B8%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F.
