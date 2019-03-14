# Exercises-10
A program to exercise functions in C
Write a program to display the following menu and perform the required tasks based on user request and output a proper message.  
For this purpose develop the following functions: 
f0(): will display the following menu and get and return user input. 
  Input S for super prime check , B for binary equivalent, W for weird prime check or Q to quit: W 
f1():  will input a positive integer and return it to the calling function. It will force user to input a positive integer (i.e. if user inputs a negative value it will re-ask user to input a positive integer till user inputs the required value). 
f2(): will receive an integer parameter and return number of digits of its binary equivalent.  
f3(): will receive an integer value (x) and another integer value representing its number of digits of x’s binary equivalent. 
It will form the binary equivalent of x and will return it to the calling function. 
f4() will receive an integer parameter and returns 1 if it is a super prime number, returns 0 otherwise.  
Super prime is a prime number whose updated values are all prime numbers until the number becomes a 1 digit value.
Number is updated with the sum of its digits. 
f5(): will receive an integer parameter, returns 1 if it is a prime number, returns 0 otherwise. 
f6(): will receive an integer parameter, returns sum of its digits.  
f7(): will receive an integer parameter and outputs a message if the received integer is weird prime or not. 
An integer is a weird prime, if it is a prime and all the numbers created by removing its digits from left to right and right to left are all prime numbers. 
For example 3797 is a prime number and the numbers created from it by removing digits from left to right: 797, 97, and 7 and the numbers created from it by removing digits from right to left: 3797, 379, 37, and 3 are all primes.  
Sample Run: Input S for super prime calculation, B for binary calculation, W for weird prime or Q to quit: W 
Input an integer: 3797  
3797  is a weird prime. 
Input S for super prime calculation, B for binary calculation, W for weird prime or Q to quit: S 
……. 
