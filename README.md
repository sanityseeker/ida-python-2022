# Семинары групп 11 и 12 на курсе "Введение в программирование", майнор ИАД 2022.

Ссылки:
 - [Wiki курса](http://wiki.cs.hse.ru/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5_%D0%B2_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_22/23_(%D0%BC%D0%B0%D0%B9%D0%BD%D0%BE%D1%80_%D0%98%D0%90%D0%94))
 - [Ведомость](https://docs.google.com/spreadsheets/d/1VUACNvvtewTJZYF986zfNhNiLKQ1F_ubPgDMQygrBpA/)
 - [Плейлист с записями семинаров на YouTube](https://www.youtube.com/playlist?list=PLEwK9wdS5g0qIFUmzkfICIwdr7HR6GA38)
 - [Записи семинаров на Yandex.Disk](https://disk.yandex.ru/d/YH-3luMiEVWh3w/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5/%D0%A1%D0%B5%D0%BC%D0%B8%D0%BD%D0%B0%D1%80)
 - [Форма для сдачи бонусов](https://forms.gle/THdDf7fkVwKAbgnv8). Просьба делать один ответ на семинар. Обсуждения будут в личных сообщениях в телеграме.

## Прошедшие семираны:
- [21.09.2022](seminar_01_intro.ipynb): Первое знакомство с языком. Установка среды разработки. Переменные. Булевые операции. If. Немного про строки. Дзен Python. (+ в тексте семинара есть гайд для установки WSL)
- [28.09.2022](seminar_02_floats_fstrings.ipynb): Что такое float. Вещественные числа в Python. Слайсы. Методы работы со строками. Способы форматирования строк. 
(* успели со второй группой) Ссылки на ячейку в памяти, getrefcount(). Дисассемблирование f-string и .format().
- [05.10.2022](seminar_03_sequences.ipynb): Изменяемые и неизменяемые последовательности: bytes, list, tuple, namedtuple, array. Цикл for. List comprehensions. Генераторы. Range. Чтение и запись в файлы. Распаковка последовательностей. Эффективность array с точки зрения памяти. (* успели со второй группой) Пример циклической ссылки.
- [12.10.2022](seminar_04_hashtables.ipynb): Dict и Set, понятие хеш-таблицы. Простанство имен программы как словарь. Counter и defaultdict из модуля collections. Использование множеств для быстрой проверки на наличие элемента. Задачи: подсчет символов в строке, дедупликация с сохранением порядка, 2-sum для произвольных массивов, общие элементы в списках.
- [19.10.2022, 02.11.2022](seminar_05_6_functions.ipynb): Понятие и синтаксис функций. Positional и keyword аргументы. Области видимости. Анонимные функции. Написание генератора с помощью yield. Замыкания (closures), пример с вычислением среднего значения на потоке. Понятие рекурсии и примеры (факториал, последовательность Фибоначчи, бинпоиск). Декораторы. Замещение исходной функции декоратором. Использование @wraps для сохранения документации декорируемой функции. Декораторы с параметрами. Примеры декораторов (время, lru cache). (на дополнительное чтение) модуль Bisect.  
- [09.11.2022](seminar_07_regexp.ipynb): Основные команды для работы с файлами и папками в терминале. Создание запускаемых файлов. Разрешения файлов в unix-подобных системах. Регулярные выражения, примеры (lookahead/lookbehind, замена времени на фразу, удаление списка стопслов).
- [16.11.2022](seminar_08_classes.ipynb): Принципы ООП. Классы в Python. Self. Magic методы. Написание класса Complex с частью арифметических операций. Raise для выбрасывания исключений. isinstance и issublcass. Copy и Deepcopy на примере объектов класса Complex и объектов класса Bus.
- [23.11.2022](seminar_09_pre_midterm.ipynb): Решение задачек перед контрольной работой
- [23.11.2022](seminar_09_descriptors.ipynb): @staticmethod, @classmethod, @property. Понятие дескриптора. Задание getter, setter, deleter для атрибутов класса.
- [07.12.2022](seminar_10_inheritance.ipynb): Элементы функционального программирования -- itemgetter, attrgetter, methodcaller, filter, map, reduce, accumulate. Наследование. Обработка исключений.
- [14.12.2022](seminar_11_various.ipynb): Python WTF??!!


## Бонусы
В конце семинаров я предлагаю решить задачи для практики по теме. Сдавать их можно до разбора на одном из последующих семинаров. Можно получить 1 балл с одного семинара.
Решение части таких задач является необходимым, но недостаточным условием получения автомата.

Если не сказано обратного, бонусы принимаются в течение двух недель после семинара.

- Семинар 1: ~"Забегая вперед, однострочники"~
- Семинар 2: ~"foo:foo", "Форматирование по целочисленной точности", "Удаление стопслов в строке", "Fun". (нужно сделать 3 из 4)~
- Семинар 3: ~"Палиндром", "Два числа с суммой N", "Три числа с суммой N"~
- Семинар 4: ~"TF-IDF", "Анаграммы" (каждая на 1 балл)~
- Семинар 6: ~"Декоратор-кэш" (2 балла)~
- Семинар 7: ~"E-mails", "Погенерируем пароли" (каждая на 1 балл)~
- Семинар 10: ~"Поисковый индекс", "Декоратор-assert типов" (каждая на 2 балла)~

---

Рекомендуемые материалы:
  - Прекраснейшая [документация Python](https://docs.python.org),
  - Курсы Георгия Курячего ([web](http://uneex.org/LecturesCMC), [youtube](https://www.youtube.com/channel/UC6m3WI2mgZLj3LgNYWQNH6g/featured)),
  - ["Fluent Python, 2nd Edition", written by Luciano Ramalho](https://www.oreilly.com/library/view/fluent-python-2nd/9781492056348/),
  - ["Python Cookbook, 3rd Edition", David Beazley, Brian K. Jones](https://www.oreilly.com/library/view/python-cookbook-3rd/9781449357337/)
