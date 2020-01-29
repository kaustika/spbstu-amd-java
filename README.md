# spbstu-amd-java

Материалы для курса по джаве у приматов.


## Дополнительные материалы

- Отличный, весьма полный [курс](https://compscicenter.ru/courses/java/nsk/2017-autumn/classes/3384/) лекций.
- Прохладный [курс](https://stepik.org/course/187/syllabus?auth=registration), но задачки порешать можно.
- Адаптивный [курс](https://stepik.org/course/2403/?auth=registration) с задачами.


## Тесты

Всего пять тестов на знание тонких и не очень мест джавы. 

Вам будут предложены фрагменты странного кода, нужно найти в них ошибки.
 
Ответы нужно будет записать в текстовый файл в формате:
- номер вопроса
- копипаст строки с ошибкой
- тип ошибки (CE, RE, LE - compile, runtime, logic соответственно)

В подготовке могут помочь [шпоры](https://github.com/winter-yuki/spbstu-amd-java/blob/master/TRICKY.md). 
(Но их не достаточно, практикуйтесь в программировании сами!)


## Лабораторный

В курсе 4 лабораторные работы. Они вместе складываются в один проект - многопоточный архиватор.

Описания: 
[первой](https://github.com/winter-yuki/spbstu-amd-java/blob/master/LAB1.md), 
[второй](https://github.com/winter-yuki/spbstu-amd-java/blob/master/LAB2.md), 
[третьей](https://github.com/winter-yuki/spbstu-amd-java/blob/master/LAB3.md), 
[четвертой](https://github.com/winter-yuki/spbstu-amd-java/blob/master/LAB4.md).


### Общие требования

- SDK 1.8 (Java8 и меньше, соответственно)
- Максимально избегайте хардкода, разделяйте код и данные. 
Например, информация о формате конфигурационного файла должна хваниться в статических полях класса-парсера
(какие символы-разделители используется и т.п.).
