import random
password="+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
pass_length = int(input("Введите желаемую длину пароля: "))

pasword=''

for i in range(pass_length):
    password+=random.choice(password)
print(password)
