# Assignment-2
#Task 1------>Check if a Number is Even or Odd
A=int(input('Enter a Number: '))
if A%2==0:
    print(A,'Is an even number.')
else:
    print(A,'is an odd number.')


#Task 2-------> Sum of Integers from 1 to 50 Using a Loop
total_sum=0
for i in range(1,51):
    total_sum=total_sum+i
print('The sum of integers from 1 to 50 is:' ,total_sum)
