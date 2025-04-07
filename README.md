# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
import random
import time

# Get user input
count = int(input("Enter the number of random numbers to generate: "))
min_val = int(input("Enter the minimum value: "))
max_val = int(input("Enter the maximum value: "))

# Seed the random number generator with current time
random.seed(time.time())

print("Pseudorandom numbers:")
for _ in range(count):
    random_number = random.randint(min_val, max_val)
    print(random_number)
```

# OUTPUT:

![Screenshot 2025-04-07 082908](https://github.com/user-attachments/assets/34d47786-2f51-442a-a62c-c4600c67ab21)

# RESULT:
Thus Pseudorandom Number Generation Using Standard library has been executed successfully.
