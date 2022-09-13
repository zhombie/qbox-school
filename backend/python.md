## Python

### Типы данных:

1. bool
2. int
3. float
4. str
5. set
6. frozenset
7. list
9. tuple
10. range
11. dict

### Работа с типами данных:

1. int:
    1. int_1 + int_2
    2. int_1 - int_2
    3. int_1 * int_2
    4. int_1 / int_2
    5. int_1 ** int_2 (power)
    7. int_1 % int_2 (mod)
    8. int_1 // int_2 (floordiv)
    9. int_1 > int_2 (gt)
    10. int_1 < int_2 (lt)
    11. int_1 >= int_1 (gte)
    12. int_1 <= int_2 (lte)
    13. int_1 == int_2 (compare)
    14. int_1 and int_2
    15. int_1 or int_2
  
2. str:
    1. .isdigit()
    2. .isnumber()
    3. .isalpha()
    4. .islower()
    5. .isupper()
    6. .strip()
    7. .lstrip()
    8. .rstrip()
    9. .capitalize()
    10. .startswith()
    11. .endswith()
    12. .split()
    13. .upper()
    14. .lower()
    15. .format()
    16. .index()
    17. .count()
    18. .zfill()
    19. .join()
    20. .removeprefix()
    21. .removesuffix()
    22. .replace()
    23. str_1 in str_2 (contains)
    24. str_1 == str_2 (compare)
    25. str_1[:] (substring)
    26. str_1[int_1:] (substring)
    27. str_1[int_1:int_2] (substring)
  
3. set:
    1. .pop()
    2. .update()
    3. .add()
    4. .remove()
    5. .difference()
    6. .clear()
    7. .intersection()
    8. .union()

4. list:
    1. .append()
    2. .extend()
    3. .sort()
    4. .clear()
    5. .index()
    6. .insert()
    7. .remove()
    8. list_1 + list_2 (add)
    9. element in list (contains), element not in list (does not contain)
    10. list_1 == list_2 (equals)

5. dict:
    1. .get()
    2. .update()
    3. .pop()
    4. .values()
    5. .keys()
    6. .items()
    7. .clear()
    8. .copy()
    9. del dict_1['key']
    10. 'key' in dict_1 (contains), 'key' not in dict_1 (does not contain)

### Работа со встроенными функциями:

1. Проверка:
    1. isinstance()
    2. isawaitable()
    3. issubclass()
  
2. Получение информации: 
    1. type()
  
3. Конвертация: 
    1. int()
    2. str()
    3. list()
    4. set()
    5. dict()

4. Математические операции:
    1. abs()
    2. min()
    3. max()
    4. sum()
    5. round()
    6. pow()
    7. divmod()
    
5. Итераторы:
    1. all()
    2. any()
    3. sorted()
    4. map()
    5. zip()
    6. len()
    7. next()
    8. enumerate()

7. Свойства модулей, классов/объектов: 
    1. hasattr()
    2. getattr()
    3. delattr()

8. Файлы:
    1. open()

9. Остальные:
    1. input()
    2. print()
    3. ord()
    4. ascii()

### Ключевые слова зарезервированные языком

1. and
2. as
3. assert
4. break
5. class
6. continue
7. def
8. del
9. elif
10. else
11. except
12. False
13. finally
14. for
15. from
16. global
17. if
18. import
19. in
20. is
21. lambda
22. None
23. nonlocal
24. not
25. or
26. pass
27. raise
28. return
29. True
30. try
31. while
32. with
33. yield

### Функции

1. Стандартные

2. Вложенные

3. Декораторы

4. Видимость на уровне файла/модуля (приватный/публичный)

5. Входные данные (параметры/аргументы)
    1. Названные параметры
    2. Аргументы по умолчанию

> Параметры - передаваемые значения во время определения функции
> Аргументы - полученные значения внутри функции

6. Возвращаемые данные

7. Анонимные функции (lambda)

8. \*args

9. \*\*kwargs

10. Рекурсия

### Классы

1. Декораторы:
    1. @staticmethod()
    2. @classmethod()
    3. @property

2. Создание экземляра/объекта

3. Наследование

4. Абстрактный класс
    1. @abc.ABC
    2. @abstractmethod

5. enum класс
    1. @enum.unique
    2. enum.Enum

6. self/cls

7. Вложенный класс (класс внутри класса)

8. Методы

9. Видимость (приватный/публичный)

10. Конструктор

11. Переопределение метода
