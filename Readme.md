# Program 2. WAP to accept a number 'n' to compute the following:
# a. check if 'n' is prime or not
<br>
code= n = eval(input("enter value"))
<br>
if n>1:
<br

    for i in range(2,n):
  <br>
        if n % 1 == 0:
        <br>
            print(n,"not a prime number")
            <br>
            break
            <br>
    else:
    <br>
        print(n,"prime number")
        <br>
else:
<br>
    print(n,"not a prime number")
    
![Screenshot 2024-11-06 101053](https://github.com/user-attachments/assets/4e7ee977-3bf7-4ed2-b904-61f0282fcf47)
![Screenshot 2024-11-06 101134](https://github.com/user-attachments/assets/f2688e93-7c50-46af-8906-bd02c8a89080)

# b. generate all prime numbers till'n'
code= n = eval(input("enter value"))
<br>
for num in range(1,n):
<br>
    if num > 1:
    <br>
        for i in range (2,num):
        <br>
            if num % i == 0:
            <br>
                break
                <br>
            else:
            <br>
                print(num,end =',')
![Screenshot 2024-11-06 100027](https://github.com/user-attachments/assets/ee1b70e6-6cea-430c-be6e-f50179d47906)

# c. generate first 'n' prime numbers
code= n = eval(input("enter value"))
<br>
count = 0
<br>
number = 2
<br>
while count < n:
<br>
    for i in range(2,number):
    <br>
        if number % i == 0:
        <br>
            number +=1 
            <br>
            break
            <br>
    else:
    <br>
        print (number,end=',')
        <br>
        count += 1
        <br>
        number += 1
![Screenshot 2024-11-06 102504](https://github.com/user-attachments/assets/8002c88b-2698-4760-a485-46ce72be7548)

# d. Calculate sum of first 'n' natural number
code= n = eval(input("enter value"))
<br>
sum=0
<br>
for i in range (1,n+1):
<br>
    sum += i
    <br>
print(sum)
![Screenshot 2024-11-06 103108](https://github.com/user-attachments/assets/965ca8ee-6c4a-487d-bde0-b342238fbbe4)




