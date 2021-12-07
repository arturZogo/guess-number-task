# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](https://github.com/arturZogo/guess-number-task/edit/master/README.md/README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](.README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[5. Результат](.README.md#Результат)    
[6. Выводы](.README.md#Выводы) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](_)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
Учимся писать хороший код на python


### Краткая информация о данных
Код был написан заблаговременно разработчиками курса, оставалось только добавить бинарный алгоритм поиска для уменьшения попыток при поиске загаданного числа.
  
:arrow_up:[к оглавлению](.README.md#Оглавление)


### Этапы работы над проектом  
1. Создание функции, в которой компьютер сам загадывает и угадывает число
2. Создание функции, в которой есть бинарный алгоритм поиска числа
3. Воспроизведение функции 1000 раз для поиска среднего результата, цель - минимизировать количество шагов, за которые компьютер угадывает число

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
При воспроизведении кода, в котором загадывается число от 1 до 100, средний результат поиска - 5 шагов.
При увеличении диапазона до 1000, средний результат увеличивается до 8 шагов.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
Бинарный поиск позволяет рабоатать с большими диапазонами чисел.

:arrow_up:[к оглавлению](.README.md#Оглавление)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль arturZogo /
guess-number-task
