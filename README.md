# EX-NO-6-Pseudo-Random-Number
## NAME: SIVAHARIBALAN K
## REG NO: 212224220103

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:

Step 1: Start the program.

Step 2: Import the required libraries (random and time).

Step 3: Seed the random number generator using the current time (random.seed(time.time())).

Step 4: Get the number of random numbers to generate from the user.

Step 5: Get the minimum and maximum values from the user.

Step 6: Pass the number of iterations using a loop and generate random numbers within the given range.

Step 7: Print the generated random numbers.

Step 8: End the program.

# PROGRAM:

```python
import random
import time

random.seed(int(time.time()))
count = int(input("Enter the number of random numbers to generate: "))
min_val = int(input("Enter the minimum value: "))
max_val = int(input("Enter the maximum value: "))
print("Pseudorandom numbers:")
for _ in range(count):
    random_number = random.randint(min_val, max_val)
    print(random_number)
```
# OUTPUT:

<img width="892" height="481" alt="image" src="https://github.com/user-attachments/assets/02844e2e-e0d8-4828-b0c9-9355bb208aa1" />

# RESULT:

Thus the program to implement Pseudorandom Number Generation is successfully executed.
