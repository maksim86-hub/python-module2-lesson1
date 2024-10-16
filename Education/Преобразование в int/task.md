В языке программирования Python часто возникает необходимость преобразовывать строки в целые числа. Это может быть полезно, когда мы получаем данные от пользователя или загружаем их из файлов, и нужно работать с ними как с числами.

### 1. Функция `int()`

Основной способ преобразования строки в целое число — это использование функции `int()`. Эта функция принимает строку, содержащую числовое значение, и возвращает соответствующее целое число. 

**Пример:**

```python
number_str = "42"  # строка
number_int = int(number_str)  # преобразование в целое число
print(number_int)  # Вывод: 42
```

Если строка не содержит корректного числового значения, будет вызвано исключение `ValueError`.

### 2. Работа с системами счисления

Функция `int()` также позволяет преобразовывать строки, представляющие числа в различных системах счисления. Например, чтобы преобразовать строку, представляющую двоичное число, в десятичное, нужно указать основание системы счисления:

**Пример:**

```python
binary_str = "1010"
decimal_number = int(binary_str, 2)  # преобразование из двоичной системы
print(decimal_number)  # Вывод: 10
```

### 3. Выполните следующий код:

```python
number_str = "123"
number_int = int(number_str)  # Преобразуем строку в целое число
print(f"Строка '{number_str}' преобразована в целое число: {number_int}")
```
