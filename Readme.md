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

# Program 2. WAP to accept a number 'n' to compute the following:

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
