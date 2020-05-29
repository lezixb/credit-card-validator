# Here are the rules for a valid Credit Card numbers
## Number must be 16 digits, all of them must be numbers
## You must have at least two different digits represented (all of the digits cannot be the same)
## The final digit must be even
## The sum of all the digits must be greater than 16
## The following credit card numbers are valid:
### 9999-9999-8888-0000
### 6666-6666-6666-1666
## The following credit card numbers are invalid:
### a923-3211-9c01-1112 invalid characters
### 4444-4444-4444-4444 only one type of number
### 1111-1111-1111-1110 sum less than 16
### 6666-6666-6666-6661 odd final number

# Additional Requirements
## Hint: Remove the dashed from the input string before checking if the input credit card number is valid.
## Bonus: Return an object indicating whether the credit card is valid, and if not, what the error is 
### { valid: true, number: 'a923-3211-9c01-1112' } 
### { valid: false, number: 'a923-3211-9c01-1112', error: ‘wrong_length’ }

# Sample Screenshots
![](images/Capture1.png)