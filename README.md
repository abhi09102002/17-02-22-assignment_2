Number = int(input("Please Enter the Fibonacci Number Range = "))

First = 0
Second = 1
Sum = 0

for Num in range(0, Number):
    print(First, end = '  ')
    Sum = Sum + First
    Next = First + Second
    First = Second
    Second = Next

print("\nThe Sum of Fibonacci Series Numbers = %d" %Sum)


output:
enter the fibonacci range =5
0 1 1 2 3
sum of fibonacci series numbers are:7
