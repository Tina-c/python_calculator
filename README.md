# Simple Calculator (Python)

A beginner Python project that performs:

- Addition
- Subtraction
- Multiplication
- Division

## Skills Used
- Python
- Functions
- User Input
- Conditional Statements


#calculator


def add(a,b):
    return a+b
def subtract(a,b):
    return a-b
def multiply(a,b):
    return a*b
def divide(a,b):
    if b==0:
        return "cannot divide by zero"
    return a/b

print(".../Simple calculator")

a=int(input("enter number 1..2"))
b=int(input("enter number 2.."))

print("\n select choice..")
print("1.addition")
print("2.substraction")
print("3.multiplication")
print("4.division")

choice=int(input("enter choice(1-4)"))

if choice==1:
    print("result is...",add(a,b))

elif choice==2:
    print("result is...",subtract(a,b))

elif choice==3:
    print("result is...",multiply(a,b))

elif choice==4:
    print("result is...",divide(a,b))

else:
    print("invalid choice")
