# SQL PROJECT INFO21_1.0
## Part 1. Создание базы данных
1) Написать скрипт, который создаёт базу данных :white_check_mark:
2) Внести в скрипт процедуры, которые вносят данные в БД
3) внести в скрипт процедуры, которые импортируют/экспортируют данные из файла/в файл с расширением .csv
## Part 2. Изменение данных
1) Написать процедуру добавления P2P проверки
2) Написать процедуру добавления проверки Verter'ом
3) Написать триггер: после добавления записи со статутом "начало" в таблицу P2P, изменить соответствующую запись в таблице TransferredPoints
4) Написать триггер: перед добавлением записи в таблицу XP, проверить корректность добавляемой записи
## Part 3. Получение данных
1) Написать функцию, возвращающую таблицу TransferredPoints в более человекочитаемом виде
2) Написать функцию, которая возвращает таблицу вида: ник пользователя, название проверенного задания, кол-во полученного XP
3) Написать функцию, определяющую пиров, которые не выходили из кампуса в течение всего дня
4) Посчитать изменение в количестве пир поинтов каждого пира по таблице TransferredPoints
5) Посчитать изменение в количестве пир поинтов каждого пира по таблице, возвращаемой первой функцией из Part 3
6) Определить самое часто проверяемое задание за каждый день
7) Найти всех пиров, выполнивших весь заданный блок задач и дату завершения последнего задания
8) Определить, к какому пиру стоит идти на проверку каждому обучающемуся
9) Определить процент пиров, которые:
10) Определить процент пиров, которые когда-либо успешно проходили проверку в свой день рождения
11) Определить всех пиров, которые сдали заданные задания 1 и 2, но не сдали задание 3
12) Используя рекурсивное обобщенное табличное выражение, для каждой задачи вывести кол-во предшествующих ей задач
13) Найти "удачные" для проверок дни. День считается "удачным", если в нем есть хотя бы N идущих подряд успешных проверки
14) Определить пира с наибольшим количеством XP
15) Определить пиров, приходивших раньше заданного времени не менее N раз за всё время
16) Определить пиров, выходивших за последние N дней из кампуса больше M раз
17) Определить для каждого месяца процент ранних входов
## Дополнительно. Part 4. Метаданные
1) Создать хранимую процедуру, которая, не уничтожая базу данных, уничтожает все те таблицы текущей базы данных, имена которых начинаются с фразы 'TableName'.
2) Создать хранимую процедуру с выходным параметром, которая выводит список имен и параметров всех скалярных SQL функций пользователя в текущей базе данных. Имена функций без параметров не выводить. Имена и список параметров должны выводиться в одну строку. Выходной параметр возвращает количество найденных функций.
3) Создать хранимую процедуру с выходным параметром, которая уничтожает все SQL DML триггеры в текущей базе данных. Выходной параметр возвращает количество уничтоженных триггеров.
4) Создать хранимую процедуру с входным параметром, которая выводит имена и описания типа объектов (только хранимых процедур и скалярных функций), в тексте которых на языке SQL встречается строка, задаваемая параметром процедуры.
