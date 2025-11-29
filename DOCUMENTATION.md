# Документація API
## Модуль Calculator
### Функція add()
``````python
def add(a, b):
 """Додавання двох чисел"""
 return a + b
``````
**Параметри:**
- `a` (float): Перше число
- `b` (float): Друге число
**Повертає:**
- `float`: Сума двох чисел
**Приклад:**
``````python
result = add(5, 3)
print(result) # Виведе: 8
``````
### Функція divide()
``````python
def divide(a, b):
 """Ділення двох чисел"""
 if b != 0:
 return a / b
 else:
 return "Помилка: ділення на нуль!"
``````
**Параметри:**
- `a` (float): Ділене
- `b` (float): Дільник
**Повертає:**
- `float`: Результат ділення, або помилка якщо b = 0
**Приклад:**
``````python
result = divide(10, 2)
print(result) # Виведе: 5.0