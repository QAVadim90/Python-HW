# Задание 1
>1. Пользователь вводит с клавиатуры три числа. Необходимо найти сумму чисел, произведение чисел. Результат вычислений вывести на экран.

ОТВЕТ
```PYTHON
a = int(input("введите первое число: "))
b = int(input("введите второе число: "))
c = int(input("введите третье число: "))
d = a + b + c
print("сумма ваших чисел", f"{a} + {b} + {c} = {d}")
e = a * b * c
print("произведение ваших чисел =", e)
```

# Задание 2
>2. Пользователь вводит с клавиатуры три числа. Первое число — зарплата за месяц, второе число — сумма месяч- ного платежа по кредиту в банке, третье число — задол- женность за коммунальные услуги.
Необходимо вывести на экран сумму, которая останется у пользователя после всех выплат.

ОТВЕТ
```PYTHON
a = int(input("введите заработную плату: "))
b = int(input("введите ежемесячный платеж по кредиту: "))
c = int(input("введите задолженность по коммунальным услугам: "))
d = "остаток з/п"
e = a - b - c
print(d, e)
```

# Задание 3
>3. Напишите программу, вычисляющую площадь ромба. Пользователь с клавиатуры вводит длину двух его диагоналей.

ОТВЕТ
```PYTHON
a = int(input("введите высоту ромба: "))
b = int(input("введите ширину ромба: "))
c = (a * b) // 2
d = "площадь ромба"
print(d, c)
```

# Задание 4
>4. Выведите на экран надпись To be or not to be на разных строках. Пример вывода:
```PYTHON
To be
or not
to be

ОТВЕТ
print(' To be, \n or not, \n to be')
```

# Задание 4
>5. Выведите на экран надпись «Life is what happens when you're busy making other plans» John Lennon на разных строках. Пример вывода:
“Life is what happens
      when
         you’re busy making other plans”
                                     John Lennon.
ОТВЕТ
```PYTHON
print("'Life is what happens \n      when \n         you're busy making other plans' \n                                     John Lennon")
```

