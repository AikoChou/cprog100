# cprog100
Homeworks of C Programming in Fall 2011

Homework #1
------------
This program allows you to practice vi and gcc. You are required to do the following:

1. write the first program that can print an N×N multiplication table on to the screen, where N is input by scanf.

2. write the second program that can print an N×N multiplication table on to the screen, where N is input from the argument list.

Homework #2
------------
This program allows you to a game called **master mind**. In the program you have to do the following:

1. Define (input)
  1. the number of integers (N) to play with. For example, input 5 means you like to play with 5 numbers which is 1 to 5 and 
  2. number of guesses (G) and input these G integers, For example, if G = 4, you can input 1 2 3 4. 
  3. **both N and G are from argument list.**

2. Write a loop to let user to input his guesses. If both the position and number are correct, it generates an H and if only the number is correct, it generates an X. For example,
  1 2 3 4
  1 3 5 1 -> 1 H and 1 X

3. User input his guesses until his guesses are correct and the program terminates.

Homework #3
------------

1. Write a program that can input a float or double number and print out its bit pattern and vice versa.

2. Please check:
  1. Is it really that
    *1.175494350822287507968736537222245677818665556772087521508751706278417259454727172851560500000000000000000000000000000000e-38f* are the smallest floating point number as stated in the textbook. If not, what is the smallest floating point number ?
  2. What is the bit pattern of f=0.0
  3. run
  ```
  f1 = 1.175494350822287507968736537222245677818665556772087521508751706278417259454727172851560500000000000000000000000000000000e-38f;
  f2 = 1.175494350822287500e-38f;
  if( f1==f2 ) { printf(“%.100e = %.100e”, f1, f2); } else { printf(“%.100e != %.100e”, f1, f2); }
  ```
  Explain the result.
  
Homework #4
------------

Modify the program in page 170 to be a recursive function. You are required to do the following:

1. You need to create a function in addition to the main function.

2. Your recursive function must accept any number of Boolean varaiables which is defined when you run the program (by using argc and argv).

3. The Boolean equation of the Boolean variables can be any one. The simplest Boolean equation can be the one that performs the **And** operation on all the Boolean variable.

4. Running examples:
  Assume *TruthTable* is the executable file after compilation 
  
  a. TruthTable v1 & v2 & v3
    
  b. TruthTable v1 & v2 & v3 & v4 ^ v5
  
  c. TruthTable v1 & v2 | v3 | v4
  
  d. TruthTable v1 + v2 + v3 + v4 + v5 + v6 > 3
