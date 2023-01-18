# Индивидуальная практическая работа №1. Работа с 2D графикой
## Цель индивидуальной работы.
Целью выполнения индивидуальной практической работы является
закрепление материала теоретического курса. Работа с простыми
графическими примитивами. Управление касаниями сенсорного экрана.
## Указания по выбору варианта.
Соответствующий вариант работы выбирается по правилу: последняя
цифра номера зачетной книжки: n / 2 + 1. Если есть дробная часть после
деления, то она отбрасывается ( т.е. 4.5 –> 4 )
## Задания
В соответствии с индивидуальным заданием создать простое игровое
приложение, использующие возможности встроенной графической
библиотеки Skia

## Вариант 2 
Касаниями вправо-влево управлять прямоугольником-«ракеткой»,
отбивать движущийся шарик.
![222](https://user-images.githubusercontent.com/75760235/213184144-40588b9e-2dce-4c12-bdab-1b0b3cf566cd.jpg)
## Решение
#### Юнит тест на корректность работы приложения: ipr1/app/src/androidTest/java/com/eugene/ping/ExampleInstrumentedTest.kt

Программа представляет собой android приложение, созданное как проект в android studio.
Программа представляет собой простейшую реализацию игры пингпонг, где пользователь управляет касанием на экране (в данном случае
касанием мыши на эмуляторе) прямоугольником-ракеткой и отбивает
движущийся шарик. 
Против пользователя играет точно также играет компьютер, пытаясь отбивать шарик.

![1x](https://user-images.githubusercontent.com/75760235/213186107-153a373d-eb1a-4145-a21a-7c580a650e4d.png)
