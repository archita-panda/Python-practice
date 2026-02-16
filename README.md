# Python-practice
Daily python coding practice
number = int(input("Enter the number till which you want to check: "))

if number <= 1:
    print("No prime numbers in this range.")
else:
    for i in range(2, number + 1):
        is_prime = True
        
        for j in range(2, int(i**0.5) + 1):
            if i % j == 0:
                is_prime = False
                break
        
        if is_prime:
            print(i)

            
Number = int(input("entera the number:"))
if Number % 2 == 0:
    print(f"{Number} is even")
else:
    print(f"{Number} is odd")

    def check_even_odd(n):
    if n % 2 == 0:
        print(f"{n} is even")
    else:
        print(f"{n} is odd")

check_even_odd(33)

def multiplication_table(n):
    for i in range(1,11):
        print(f"{n} X {i} = {n*i}")

multiplication_table(4)
#find  the sum of n number of natural num
def sum_of_naturalnumbers(n):
    temp=0
    
    for i in range(1,n+1):
        temp+=i

    return temp
n = int(input("enter the number"))
result=sum_of_naturalnumbers(n)
print(f"The sum of the first natural numbers {n} is {result}")
def sum_of_naturalnumbers(n):
    temp=0
    
    for i in range(1,n+1):
        temp = n*(n+1)//2
    return temp
n = int(input("enter the number"))
result=sum_of_naturalnumbers(n)
print(f"The sum of the first natural numbers {n} is {result}")


#reversing a number
def revers_num(n):
    num = n
    reverse = 0
    while num> 0:
        lastdigit = num% 10
        reverse = reverse* 10 + lastdigit
        num = num//10
    return reverse
n = int(input("enter the number"))
result= revers_num(n)
print(f"the reverse form of {n} is {result}")

    
