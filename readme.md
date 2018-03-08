<h1 align="center">
Computer Science Awesome List
</h1>

## Big 0

- [Big O Notation in JavaScript](https://medium.com/cesars-tech-insights/big-o-notation-javascript-25c79f50b19b)
- [Big 0 - Linear Sum Demo](https://repl.it/@JesseShaw/linearsumdemo)

## Recursion

- [Eloquent Javascript - Recursion](http://eloquentjavascript.net/03_functions.html#h_jxl1p970Fy)


## Run Time Complexity

- [Constant time O(1)](https://repl.it/@thinkful/constant-runtime-example)
- [Logarithmic time O(log(n))](https://repl.it/@thinkful/logarithmic-num-less-than-demo)
- [Linear time O(n)](https://repl.it/@thinkful/find-min-linear-demo)
- [Polynomial time O(n^k)](https://repl.it/@thinkful/has-duplicates-polynomial-demo)
- [Exponential time O(2^n)](https://repl.it/@thinkful/count-triangle-exponential-demo)

### Comparing Run Time Complexity
<img width="400" src="https://raw.githubusercontent.com/thejesseshaw/computersciencerepository/master/big0/BigO.png" alt="Big0 complexity">

| Big-O Notation | n = 10	| n = 100	| n = 1000|
| -------------- |:--------:|:---------:| :-------:|
|O(1)            |	1	    |1	        |1        |
|O(log n)        |	3	    |6	        |9        |
|O(n)	         |10        |100        |1000     |
|O(n^2)          |100       |10000      |1000000  |
|O(2^n)          |1024      |2^100      |2^1000   |

## Binary and Bitwise Operators

- [Binary to Decimal Conversion](https://repl.it/@JesseShaw/BinaryDeceminalConversion)
- [Decimal to Binary Conversion](https://repl.it/@JesseShaw/NumericalToBinary)

## Two's Compliment

- [Interger to Twos Comp (May need to be tested further)](https://repl.it/@JesseShaw/TwosCompliment)


## Logical Operators

-[Even Odd Exercise for AND(&) Operator](https://repl.it/@JesseShaw/BitwiseAndOperatorEVENODD)
-[Or Operator Exercise](https://repl.it/@JesseShaw/orOperatorExercise)
-[Xor Operator Exercise](https://repl.it/@JesseShaw/XorOperators)
-[Not Operator](https://repl.it/@JesseShaw/notOperator)

### Interview Questions

*Write a function which sets the third bit of a number.
*Write a function which toggles the third bit of a number.
*Write a function which clears (sets to zero) the third bit of a number.
*Write a function which tells you whether the third bit of a number is set.

## Shift Operators

Write a function that takes in a decimal value and a value that represents the number of bit positions to shift left with. Return or print out the final base 10 value after the shift. Include verification

Modify your existing shift function to also calculate a right-shifted value. Compare the values which you get from your left-shift and right-shift functions.

Modify your existing shift function to also calculate a zero-fill right-shifted value. Compare the values which you get from your three different type of shift operator.

For non-negative numbers, does the zero-fill right shift operator differ from the right shift operator in terms of producing the end result? Why or why not? Eg. 11 >>> 4 vs 11 >> 4

-[Shift Operators](https://repl.it/@JesseShaw/shiftOperators)

### Interview Questions

*Write a function which doubles an integer.
*Write a function which quadruples an integer.
*Write a function which divides an integer by two, rounding down.
*Write a function which calculates 2^n.
*Write a function which calculates the Morton Number from two 8-bit integers. In a Morton Number, the bits of two numbers are interleaved. So if your inputs were: 15 (00001111) and 48 (00110000), your output would be 1450 (0000010110101010).

##Arrays

Imagine you have an array of numbers. Write an algorithm to remove all numbers less than five from the array.
You shouldn't use the .filter method here; try to write the algorithm from scratch.

-[Array less than 5 (no filter)](https://repl.it/@JesseShaw/BlushingStunningEngineer)

Imagine you have two arrays which have already been sorted. Write an algorithm to merge the two arrays into a single array, which should also be sorted. For example, if your input arrays were [1, 3, 6, 8, 11] and [2, 3, 5, 8, 9, 10], your output array should be [1, 2, 3, 3, 5, 6, 8, 8, 9, 10, 11].

### Interview Questions

Note:
You can use JavaScript's built in arrays rather than your Array object to answer these questions.

*Imagine you have an array of numbers. Write an algorithm to remove all numbers less than five from the array.
*You shouldn't use the .filter method here; try to write the algorithm from scratch.
*Imagine you have two arrays which have already been sorted. Write an algorithm to merge the two arrays into a single array, which should also be sorted. For example, if your input arrays were [1, 3, 6, 8, 11] and [2, 3, 5, 8, 9, 10], your output array should be [1, 2, 3, 3, 5, 6, 8, 8, 9, 10, 11].
*Given an array of numbers, write an algorithm to find out the products of every number, except the one at that index. For example, if the input was [1, 3, 9, 4], the output should be [108, 36, 12, 27] (i.e. [3*9*4, 1*9*4, 1*3*4, 1*3*9]).

-[May not be super efficent. Need to update](https://repl.it/@JesseShaw/ThunderousHappySystem)
