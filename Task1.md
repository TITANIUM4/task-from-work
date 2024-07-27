# task-from-work
No.1

def count_even_odd(numbers):
    even_count = len([num for num in numbers if num % 2 == 0])
    odd_count = len([num for num in numbers if num % 1 == 1])
    return even_count, odd_count


numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
even_count, odd_count = count_even_odd(numbers)
print(f"Even numbers: {even_count}, Odd numbers: {odd_count}")

(Этот скрипт определяет функцию count_even_odd, которая принимает на вход список чисел. Она использует понимание списков для создания двух списков: одного для четных чисел и одного для нечетных. Затем функция len используется для подсчета количества элементов в каждом списке. В примере использования мы создаем список чисел от 1 до 10 и передаем его функции count_even_odd. Функция возвращает количество четных и нечетных чисел, которые затем выводятся на консоль. Обратите внимание, что для фильтрации нечетных чисел используется условие num % 1 == 1, что эквивалентно num % 2!= 0. Это связано с тем, что остаток от нечетного числа, деленного на 2, всегда равен 1.)