# Homework-Py-2
Ex.1
#Пользователь вводит сумму вклада в банк и годовой процент. Найдите сумму вклада через 5 лет

x = 100 #Сумма вклада
y = 13 #Годовой процент

deposit_amount1 = (x/100 * y + x)
deposit_amount2 = (deposit_amount1/100 * y + deposit_amount1)
deposit_amount3 = (deposit_amount2/100 * y + deposit_amount2)
deposit_amount4 = (deposit_amount3/100 * y + deposit_amount3)
deposit_amount5 = (deposit_amount4/100 * y + deposit_amount4)
print(deposit_amount5)

# x = 100 #Сумма вклада
# y = 13 #Годовой процент

# deposit_amount1 = x * (1 + y / 100) ** 5
# print(deposit_amount1)
Ex.2
#Дано значение температуры в градусах Цельсия. Вывести температуру  в градусах Фаренгейта.

Degrees_Celsius = 18
Degrees_Fahrenheit = (Degrees_Celsius * 1.8) + 32
print(Degrees_Fahrenheit)
