# Звіт до роботи
## Тема: Основи програмування на Python
### Мета роботи: навчитись оформляти та здавати роботи 
---
### Виконання роботи :finnadie:

1) Створив Пітхон файл з розширенням `.ipynb` в якому виконав базові приклади. Застосувавши команду `print` виконав наступне:

- Познайомився з основними типами даних. Попрактикувався з простими змінними, списками `list`, наборами `set` та словниками `dict`:

Програма:
```Python
a = "змінна з текстом"
b = 1 # числова Змінна
c = ["a", 1, 1.25, "Слово"] # List
d = {"a": "Слово", "b": 1} # Dict
e = ("a", ) # Tuple
f = {"ss", } # Set

print(a)
print(b)
print(c)
print(d)
print(e)
print(f)
```

Результат виконання програми: :flushed:
```
змінна з текстом
1
['a', 1, 1.25, 'Слово']
{'a': 'Слово', 'b': 1}
('a',)
{'ss'}
```

- Вивів вбудовані константи:

Програма:
```Python
print("Перша константа", False)
print("Друга константа", True)
print("Третя константа", None)
```

Результат виконання програми: :flushed:
```
Перша константа False
Друга константа True
Третя константа None
```

- Виві результат роботи вбудованих функцій:

Програма:
```Python
print(abs(-12.5), f"є рівним {abs(12.5)}")
print(globals())
print(float())
```

Результат виконання програми: :flushed:
```
12.5 є рівним 12.5
{'__name__': '__main__', '__doc__': 'Automatically created module for IPython interactive environment', '__package__': None, '__loader__': None, '__spec__': None, '__builtin__': <module 'builtins' (built-in)>, '__builtins__': <module 'builtins' (built-in)>, '_ih': ['', 'a = "змінна з текстом"\nb = 1 # числова Змінна\nc = ["a", 1, 1.25, "Слово"] # List\nd = {"a": "Слово", "b": 1} # Dict\ne = ("a", ) # Tuple\nf = {"ss", } # Set\n\nprint(a)\nprint(b)\nprint(c)\nprint(d)\nprint(e)\nprint(f)', 'print("Перша константа", False)\nprint("Друга константа", True)\nprint("Третя константа", None)', 'print(abs(-12.5), f"є рівним {abs(12.5)}")\nprint(globals())\nprint(float())'], '_oh': {}, '_dh': [WindowsPath('c:/Users/niger/Desktop/Навчання/ООП/JOPA/Лаба 2')], 'In': ['', 'a = "змінна з текстом"\nb = 1 # числова Змінна\nc = ["a", 1, 1.25, "Слово"] # List\nd = {"a": "Слово", "b": 1} # Dict\ne = ("a", ) # Tuple\nf = {"ss", } # Set\n\nprint(a)\nprint(b)\nprint(c)\nprint(d)\nprint(e)\nprint(f)', 'print("Перша константа", False)\nprint("Друга константа", True)\nprint("Третя константа", None)', 'print(abs(-12.5), f"є рівним {abs(12.5)}")\nprint(globals())\nprint(float())'], 'Out': {}, 'get_ipython': <bound method InteractiveShell.get_ipython of <ipykernel.zmqshell.ZMQInteractiveShell object at 0x000002AFA4A0FE50>>, 'exit': <IPython.core.autocall.ZMQExitAutocall object at 0x000002AFA4A0CF70>, 'quit': <IPython.core.autocall.ZMQExitAutocall object at 0x000002AFA4A0CF70>, '_': '', '__': '', '___': '', 'os': <module 'os' from 'c:\\Users\\niger\\AppData\\Local\\Programs\\Python\\Python310\\lib\\os.py'>, 'sys': <module 'sys' (built-in)>, '__vsc_ipynb_file__': 'c:\\Users\\niger\\Desktop\\Навчання\\ООП\\JOPA\\Лаба 2\\Dear Daily, today I will suicide.ipynb', '_i': 'print("Перша константа", False)\nprint("Друга константа", True)\nprint("Третя константа", None)', '_ii': 'a = "змінна з текстом"\nb = 1 # числова Змінна\nc = ["a", 1, 1.25, "Слово"] # List\nd = {"a": "Слово", "b": 1} # Dict\ne = ("a", ) # Tuple\nf = {"ss", } # Set\n\nprint(a)\nprint(b)\nprint(c)\nprint(d)\nprint(e)\nprint(f)', '_iii': '', '_i1': 'a = "змінна з текстом"\nb = 1 # числова Змінна\nc = ["a", 1, 1.25, "Слово"] # List\nd = {"a": "Слово", "b": 1} # Dict\ne = ("a", ) # Tuple\nf = {"ss", } # Set\n\nprint(a)\nprint(b)\nprint(c)\nprint(d)\nprint(e)\nprint(f)', 'a': 'змінна з текстом', 'b': 1, 'c': ['a', 1, 1.25, 'Слово'], 'd': {'a': 'Слово', 'b': 1}, 'e': ('a',), 'f': {'ss'}, '_i2': 'print("Перша константа", False)\nprint("Друга константа", True)\nprint("Третя константа", None)', '_i3': 'print(abs(-12.5), f"є рівним {abs(12.5)}")\nprint(globals())\nprint(float())'}
0.0
```

- Ознайомився з циклами. Написав код який демонструє роботу циклів:

Програма:
```Python
letters = ["a", "b", "c"]
for i in range(len(letters)):
    print(f"На позиції {i} знаходиться буква {letters[i]}")

for i in range(5):
    print(i)
    i = 5 

letters = ["f", "e", "j"]
for i in range(len(letters)):
    print(f"Чого на цій позиції {i} знаходиться це {letters[i]}")
```

Результат виконання програми: :flushed:
```
На позиції 0 знаходиться буква a
На позиції 1 знаходиться буква b
На позиції 2 знаходиться буква c
0
1
2
3
4
Чого на цій позиції 0 знаходиться це f
Чого на цій позиції 1 знаходиться це e
Чого на цій позиції 2 знаходиться це j
```

- Ознайомився з розгалуженнями. Написав код який демонструє роботу розгалужень

Програма:
```Python
A = True
print("Значить А=True" if A else "Значить А=False")

if 1 > 2:
    print("Ну цей вот")
else:
    print("А тут той вот")

if 2 > 1:
    print("Ну цей вот")
else:
    print("А тут той вот")
```

Результат виконання програми: :flushed:
```
Значить А=True
А тут той вот
Ну цей вот
```

- Написав код з помилкою:

Програма:
```Python
A = 0
try:
    print("Що буде якщо", 10/A, "?")
except Exception as e:
    print(e)
finally:
    print("А вот воно що!")

A = 5
try:
    print("Ну цей вот", 10/A, "?")
except Exception as e:
    print(e)
finally:
    print("Получилось/Неполучилось")
```

Результат виконання програми: :flushed:
```
division by zero
А вот воно що!
Ну цей вот 2.0 ?
Получилось/Неполучилось
```

- Напиав код з контекст-менеджером:

Програма:
```Python
with open("JoJo.txt", "r") as f:
    for line in f:
        print(line)
```

Результат виконання програми: :flushed:
```
Output exceeds the size limit. Open the full output data in a text editor
drh

st

h

dtry

kj

fyul



uho;



hu



rtd

huer
...

h

io;
```

- Написав код з використанням Лямбди:

Програма:
```Python
this_is_lambda = lambda first, last: f'Цей код написав: {first} {last}'
print("Це просто функція:", this_is_lambda)
print("Це її виклик:", this_is_lambda('Богдан', 'Бугиль'))

gta = lambda x: x*x
print(gta(5))
```

Результат виконання програми: :flushed:
```
Це просто функція: <function <lambda> at 0x000002AFA6C4F520>
Це її виклик: Цей код написав: Богдан Бугиль
25
```

### Висновок: під час виконання даної лабораторної роботи я навчився використовувати основні конструкції в Python :flushed:
> у висновку потрібно відповісти на запитання:
- :question: Що зроблено в роботі; створено прогу і перевірено 
- :question: Чи досягнуто мети роботи; Yes
- :question: Які нові знання отримано; Ci
- :question: Чи вдалось відповісти на всі питання задані в ході роботи; No
- :question: Чи вдалося виконати всі завдання; Yes
- :question: Чи виникли складності у виконанні завдання; звісно, можете побачити по результам того що програма видала (там між ними 30 хв різниці)
- :question: Чи подобається такий формат здачі роботи (Feedback); Завжди мріяв (нє)
- :question: Побажання для покращення (Suggestions); го в майн зіграємо, будете для мене ресурси приносити, а я в свою чергу добудую вулицю в Італійському стилі
---