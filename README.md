# Домашнее задание по Python
## Задание
Написать функцию, которая принимает список чисел и возвращает их сумму.
## Решение
```python
def sum_numbers(numbers):
    return sum(numbers)
# Пример:
numbers = [1, 2, 3, 4, 5]
result = sum_numbers(numbers)
print(f"Сумма чисел {numbers} = {result}")