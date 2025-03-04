# Assignment2_task_1

num = int(input('Enter a number: '))
if num%2==0:
    print(num,'is an even number.')
else:
    print(num,'is an odd number.')

This Python program prompts the user to enter a number and checks if it is even or odd. It uses the modulo operator (%) to determine if the number is divisible by 2.

If the remainder of the division is 0 (num % 2 == 0), the number is even.
If the remainder is not 0, the number is odd.

# Assignment2_task_2

total_sum=0                       # Initializes a variable to store the sum of the integers.
for m in range(1,51):                  #Uses a for loop to iterate over numbers from 1 to 50.
    total_sum+=m                         # Calculates the sum of all integers in this range.
print('The sum of numbers from 1 to 50 is:',total_sum)

    
