# Assignment-3-
# Input three numbers
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

# Finding the greatest number
if a >= b and a >= c:
    print("Greatest number is:", a)
elif b >= a and b >= c:
    print("Greatest number is:", b)
else:
    print("Greatest number is:", c)
num = int(input("Enter a number: "))



if num % 2 == 0:
    print("The number is Even")
else:
    print("The number is Odd")




ch = input("Enter a character: ")

if ch.isalpha():   # check if it is an alphabet
    if ch.isupper():
        print("Uppercase letter")
    else:
        print("Lowercase letter")
else:
    print("Not an alphabet character")
