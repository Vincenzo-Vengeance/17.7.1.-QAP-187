multipl = 1 # переменная для подсчета произведения чисел
for i in range(1, 11):
    if i % 2 == 0: 
        continue #пропуск итерации, если число четное
    else:
        i % 2 != 0 
        multipl *= i
print("Произведение нечетных чисел", multipl)
