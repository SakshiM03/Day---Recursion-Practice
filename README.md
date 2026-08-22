#1. recursion_basic.py
def countdown(n):
    if n == 0:
        print("Done!")
        return

   print(n)
    countdown(n - 1)


countdown(5)
#2. factorial_recursion.py
def factorial(n):
    if n == 0 or n == 1:
        return 1

   return n * factorial(n - 1)


num = int(input("Enter a number: "))

print("Factorial:", factorial(num))
