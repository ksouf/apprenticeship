# Kata Week 1

## The FizzBuzz Kata

    Write a program that prints the numbers from 1 to 100. But for multiples of three print "Fizz"
    instead of the number and for the multiples of five print "Buzz". For numbers which are multiples of both
    three and five print "FizzBuzz".


## String Sum Kata

    Write a simple String Sum utility with a function string Sum(string num1, string num2),
    which can accept only natural numbers and will return their sum. 
    Replace entered number with 0 (zero) if entered number is not a natural number.
    Stat with a simplest test case with an empty string
    Create a simple method string Sum(string num1, string num2)
    Write a test to pass small numbers and refactor, if test passed
    try to write more code and refactor


## String Calculator Kata (via Roy Osherove)

    Create a simple String calculator with a method int Add(string numbers). The method can take 0, 1 or 2 numbers,
    and will return their sum (for an empty string it will return 0). For example "" or "1" or "1,2".
    
    Start with the simplest test case of an empty string and move to 1 and two numbers
    Remember to solve things as simply as possible so that you force yourself to write tests you did not think about
    Remember to refactor after each passing test
    
    Allow the Add method to handle an unknown amount of numbers
    Allow the Add method to handle new lines between numbers (instead of commas).
        the following input is ok: "1\n2,3" (will equal 6)
        the following input is NOT ok: "1,\n" (not need to prove it - just clarifying)
    
    Support different delimiters. To change a delimiter,
    the beginning of the string will contain a separate line that looks like this: [delimiter]\n[numbers...], 
    for example ;\n1;2 should return three where the default delimiter is ; .
        he first line is optional. all existing scenarios should still be supported
    Calling Add with a negative number will throw 
    an exception "negatives not allowed" - and the negative that was passed.
        if there are multiple negatives, show all of them in the exception message


