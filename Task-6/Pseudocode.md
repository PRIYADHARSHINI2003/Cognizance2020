#### PROGRAM TO FIND OUT IF A GIVEN NUMBER IS AN AMSTRONG NUMBER OR NOT
``` 
Armstrong number is a number that is equal to the sum of cubes of its digit.Ex: 153,371.
```
 * Ask the user to enter a number to check if it is an armstrong number n .

* We need to obtain each digit number to calculate the sum of cube of each digit.

* Initialize sum=0 ,n. Use while loop with the condition given number n is not equal to 0 (n!= 0)

* Inside the while loop each digit of the given number can be obtained by using modulus operator(%)

* The remainder of a number when it is divided by 10 gives the last digit of the number
```
 Reminder=n % 10
 ```

* At the end of each loop 
``` 
n=n/10 
```
is taken to find consequent digits of the number.

* Sum of cube of each number is calculated by 
``` 
 Sum+=Remider *Reminder * Reminder
 ```

* We compare the Sum with the original number and conclude if it is Armstrong number or not