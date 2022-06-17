#Multiplication table using for loop

n = int(input("Enter the number: "))

for i in range(1, 11):
    
    print(f'{i} * {n} = {i * n}')
    
    
    
#Multiplication Table using while loop

n = int(input("Enter the number: "))

i = 1

while i <= 10:
    
    print(f'{i}*{n} = {i * n}')
    
    i = i + 1
