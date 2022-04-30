Домашнее задание для Netology.ru для курса Java Developer

Описание и инструкция к выполнению [здесь](https://github.com/netology-code/jd-homeworks/tree/master/jvm/README.md)

## Решение

* Выделение области памяти для Heap (A)
* Выгрузка совместно используемых классов (В)
  !["Foto"](img/1.png "Foto")
* Сборщик мусора уменьшает размер выделенной памяти
  !["Foto"](img/2.png "Foto")
* Загрузка классов из пакета в Metaspace

``` css
  loading io.vertx
  loaded 529 classes
  ``` 

!["Foto"](img/3.png "Foto")

``` css
  loading io.netty
  loaded 2117 classes
  ``` 

!["Foto"](img/4.png "Foto")

``` css
  loading org.springframework
  loaded 869 classes
  ``` 

!["Foto"](img/5.png "Foto")

* Увеличение памяти в куче
    * А - выделенная память
    * В - используемая память
      !["Foto"](img/6.png "Foto")
* Создание объектов к куче
  !["Foto"](img/7.png "Foto")
* Работа сборщика мусора
  !["Foto"](img/8.png "Foto")
* Завершение программы