## Week 3

#### Game of Life :

	Your task is to write a program to calculate the next
	generation of Conway's game of life, given any starting
	position. You start with a two dimensional grid of cells,
	where each cell is either alive or dead. The grid is finite,
	and no life can exist off the edges. When calculating the
	next generation of the grid, follow these four rules:

	1. Any live cell with fewer than two live neighbours dies,
	   as if caused by underpopulation.
	2. Any live cell with more than three live neighbours dies,
	   as if by overcrowding.
	3. Any live cell with two or three live neighbours lives
	   on to the next generation.
	4. Any dead cell with exactly three live neighbours becomes
	   a live cell.

	Examples: * indicates live cell, . indicates dead cell

	Example input: (4 x 8 grid)
	4 8
	........
	....*...
	...**...
	........

	Example output:
	4 8
	........
	...**...
	...**...
	........

### The OddEven Kata
	- Write a program that prints numbers within specified range lets say 1 to 100. If number is odd print 'Odd'
	  instead of the number. If number is even print 'Even' instead of number. Else print number [hint - if number is Prime].

#### Steps :

	Lets divide into following steps:
	- Prints numbers from 1 to 100
	- Print "Even" instead of number, if the number is even, means divisible by 2
	- Print "Odd" instead of number, if the number is odd, means not divisible by 2 but not divisible by itself too [hint - it should not be Prime]
	- Print number, if it does not meet above two conditions, means if number is Prime
	- Make method to accept any number of range [currently  we have 1 to 100]
	- Create a new method to check Odd/Even/Prime of a single supplied method

### The PrimeFactor Kata (via [Uncle Bob](http://butunclebob.com/ArticleS.UncleBob.ThePrimeFactorsKata))

### The PrimeComposite Kata
	- Write a program that prints numbers within specified range lets say 1 to 100. 
	- If number is ```prime``` print 'prime' instead of the number. 
	- If number is ```composite``` but not ```even``` print 'composite' instead of number.
	- Else print number. 
	- Reference(s)
		- [Prime numbers](https://en.wikipedia.org/wiki/Prime_number), 
		- [Composite numbers](https://en.wikipedia.org/wiki/Composite_number), 
		- [odd even](https://en.wikipedia.org/wiki/Parity_(mathematics))
  
### Steps   
	- Prints numbers from 1 to 100.
	- Print "Prime" instead of number, if the number is prime, means ```number greater than 1 that has no positive divisors other than 1 and itself```.
	- Print "Composite" instead of number, if the number is composite, means ```number has at least one positive divisor other than one or the number itself. In other words, a composite number is any integer greater than one that is not a prime number``` but not a ```even number```.
	- An even number is ```an integer is even if it is 'evenly divisible' by two```.
	- Print number, if it does not meet above two conditions.
	- Make method to accept any number of range [currently  we have 1 to 100].
	- Create a new method to check Prime/Composite of a single supplied method.

