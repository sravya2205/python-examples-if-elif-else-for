#program to print is it positive ,negative,zero
num=int(input())
if num>0:
    print("positive")
elif num<0:
    print("negative")
else:
    print("zero")

    #program to print if a number is even or odd
num=int(input())
if num in range(1,80):
    if num%2==0:
        print("even")
    else:
        print("odd")

        #program to check leap year
year=int(input())
if year%400==0 and year%100==0:
    print("leap year")
else:
    print("not a leap year")

    #program to check whether it is a prime number or not
num=int(input())
flag="false"
if num==1:
    print(f"{num} is not a prime number")
elif num>0:
    for i in range(2,num):
        if(num%i==0):
            flag="true"
            break
if flag=="true":
    print(f"{num} is not a prime number")
else:
    print(f"{num} is a prime number")

    #program to print prime numbers between 2 to 10
for num in range(1,11):
    if num>1:
        for i in range(2,num):
            if num%i==0:
                break
        else:
            print(num)

            #factorial program
num=int(input())
factorial=1
if num<0:
    print("factorial doesnot exist for negtaive numbers")
elif num==0:
    print(f"factorial of {num} is 1")
else:
    for i in range(1,num+1):
        factorial=factorial*i
    print(factorial)

    #python program to display multiplication
num=int(input())
for i in range(1,11):
    print(f"{num} * {i} = {num*i}")
