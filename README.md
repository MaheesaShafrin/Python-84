# Python-84
Python program to print Fibonacci series using iteration
a = 0
b = 1
n = int(input("Enter the number of terms in the sequence: "))

if n <= 0:
    print("Enter a positive integer")
elif n == 1:
    print(a)
else:
    print(a, b, end=" ")
    count = 2
    while count < n:
        c = a + b
        print(c, end=" ")
        a, b = b, c
        count += 1


Output:
Enter the number of terms in the sequence: 7
0 1 1 2 3 5 8 
