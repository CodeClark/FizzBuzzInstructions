# FizzBuzz Instructions

# Task Description

For the numbers 1 to 100:

* For multiples of 3 print Fizz
* For multiples of 5 print Buzz
* For multiples of 3 and 5 print FizzBuzz
* For all other numbers, you can just print the number

Hint : 
If something is a multiple of a given number it means you can devide it by that number and it leaves no remainder i.e. remainder will be 0
e.g: 
 * 6 / 3 = 2 (no remainder so print Fizz) 
 * 6 / 5 = 1.2 (with .2 remainder so print the number)
 * 10 / 5 = 2 (no remainder so print Buzz)

To work out if it is a multiple of both 3 and 5 you can perform the tests separately ( .e.g. if this or this then that ) 
or 
Perform the check with the lowest number that can be divided by both 3 and 5 leaving no remainder. 
In the case of 3 and 5, the lowest number would be 15 because they both divide this number with no remainder but not a number lower than 15
( 15 / 3 = 5 and 15 / 5 = 3 )

# Example Result for first 15 numbers


```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```


# Problems

If Visual Studio code gives you odd errors about not being able to find main class or other errors which are clearly wrong you may need to clear java workspace

`F1 ->Clean the java language server workspace`

