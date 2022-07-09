# CREDIT-CARD-VALIDATOR
In this project we used the Luhn’s Algorithm to verify wether a number is a valid credit card number or not.
A credit card number must be between 13 to 16 digits included.
It can start with 4,5,6 or 37.
And as per Luhn’s Algorithm we multiple every second digit with 2 . iF the digit become a double digit then we add its two digit.
Finally we find the sum of all the digit if it is divisible by 10 then the number is valid.
The algorithm is used to prevent any mistyoping which may happen while filling in the number.
The time complexity is O(n) and Auxillary space is O(1).
