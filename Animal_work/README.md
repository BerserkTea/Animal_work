# Итоговая работа по блоку специализация

<a href="task/Итоговая%20аттестация.pdf" target="_blank">Файл задания</a>

# Ход выполнения

## Linux

### Задание 1 
Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека).

Создание файлов

![](image/img_001.png)

Объединение, переименование файлов

![](image/img_002.png)


### Задание 2

Создать директорию, переместить файл туда. 

![](image/img_003.png)

### Задание 3 

Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.

![](image/img_004.png)

### Задание 4

Установить и удалить deb-пакет с помощью dpkg. 

![](image/img_005.png)
![](image/img_006.png)

### Задание 5

Выложить историю команд в терминале ubuntu



![](image/img_007.png)
### Задание 6 

Нарисовать диаграмму, в которой есть класс родительский класс, домашние
животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
войдут: Лошади, верблюды и ослы).
![](image/img_024.png)



### Задание 7\8

В подключенном MySQL репозитории создать базу данных “Друзья
человека”
Создать таблицы с иерархией из диаграммы в БД

![](image/img_008.png)

![](image/img_009.png)

### Задание 9

Заполнить низкоуровневые таблицы именами(животных), командами
которые они выполняют и датами рождения

![](image/img_012.png)

![](image/img_013.png)


### Задание 10

Удалить из таблицы верблюдов, т.к. верблюдов решили перевезти в другой
питомник на зимовку. 

```sql
DELETE FROM camel;
```

![](image/img_014.png)

Объединить таблицы лошади, и ослы в одну таблицу.

![](image/img_015.png)

### Задача 11

Создать новую таблицу “молодые животные” в которую попадут все
животные старше 1 года, но младше 3 лет и в отдельном столбце с точностью
до месяца подсчитать возраст животных в новой таблице

![](image/img_016.png)

![](image/img_017.png)

![](image/img_018.png)

### Задача 12

Объединить все таблицы в одну, при этом сохраняя поля, указывающие на
прошлую принадлежность к старым таблицам.

![](image/img_019.png)


