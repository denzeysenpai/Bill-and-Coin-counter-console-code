num1 = float(input("num1: "))

num = ((num1-(num1 % 1000))/1000)
num2 = (((num1 % 1000) - ((num1 % 1000) % 500)) / 500)
num3 = ((((num1 % 1000) % 500) - (((num1 % 1000) % 500) % 200)) / 200)
num4 = (((num1 % 500) % 200) - (num1 % 500) % 100) / 100
num5 = ((((num1 - (num1 % 50)) % 500) % 200) % 100) / 50
num6 = (((((num1 % 1000) % 500) % 200) % 100) % 50) / 20
num7 = (((num1 % 50) % 20) - ((num1 % 50) % 20) % 10) / 10
num8 = (((num1 % 20) % 10) - ((num1 % 20) % 10) % 5) / 5
num9 = (((num1 % 50) % 5) - ((num1 % 50) % 5) % 2) % 10

if num1 >= 1000:
    print("1000 peso bill: " + str(round(num)))
if num2 >= 1:
    print("500 peso bill: " + str(round(num2)))
if num3 >= 1:
    print("200 peso bill: " + str(round(num3)))
if num4 >= 1:
    print("100 peso bill: " + str(round(num4)))
if num5 >= 1:
    print("50 peso bill: " + str(round(num5)))
if num6 >= 1:
    print("20 peso bill: " + str(round(num6)))
if num7 >= 1:
    print("10 peso coin: " + str(round(num7)))
if num8 >= 1:
    print("5 peso coin: " + str(round(num8)))
if num9 >= 1:
    print("1 peso coin: " + str(round(num9)))

# How to get Centavos
num11 = num1
if round(num11) > num11:
    total = round(num11) - num11
    fin = round(total, 1)
    last = 1 - fin
else:
    total = round(num11) - num11
    fin = round(total, 1)
    last = fin * -1

print("Centavos: " + str(round(last * 100)))