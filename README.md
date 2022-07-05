# 30DaysOfCode of HackerRank -Javascript :computer:
My Java Scripts solutions for the 30 Days Of Code challenges on [HackerRank](https://www.hackerrank.com/domains/tutorials/30-days-of-code).
## Day 0 - Hello, World.
**Input Format:** _A single line of text denoting  (the variable whose contents must be printed)._

**Output Format:** _Print Hello, World. on the first line, and the contents of  on the second line._

**Sample Input**
```
  Welcome to 30 Days of Code!
```

**Sample Output**
```
  Hello, World. 
  Welcome to 30 Days of Code!
```
## Day 1 - Data Types
**Task:** _The variables i, d, and s are already declared and initialized for you. You must:_

1. Declare  variables: one of type int, one of type double, and one of type String.
2. Read  lines of input from stdin (according to the sequence given in the Input Format section below) and initialize your  variables.
3. Use the  operator to perform the following operations:
   - Print the sum of  plus your int variable on a new line.
   - Print the sum of  plus your double variable to a scale of one decimal place on a new line.
   - Concatenate  with the string you read as input and print the result on a new line.

**Input Format:** 
- The first line contains an integer that you must sum with .
- The second line contains a double that you must sum with .
- The third line contains a string that you must concatenate with .

**Output Format:** _Print the sum of both integers on the first line, the sum of both doubles (scaled to  decimal place) on the second line, and then the two concatenated strings on the third line._

**Sample Input**
```
  12
  4.0
  is the best place to learn and practice coding!
```

**Sample Output**
```
  16
  8.0
  HackerRank is the best place to learn and practice coding!
```
## Day 2 - Operators
**Task:** _Given the meal price (base cost of a meal), tip percent (the percentage of the meal price being added as tip), and tax percent (the percentage of the meal price being added as tax) for a meal, find and print the meal's total cost. Round the result to the nearest integer._

**Input Format:** 
  There are  lines of numeric input:
    1. The first line has a double, meal_cost (the cost of the meal before tax and tip).
    2. The second line has an integer, tip_percent (the percentage of meal_cost being added as tip).
    3. The third line has an integer, tax_percent (the percentage of meal_cost being added as tax).

**Output Format:** _print the meal's total cost._

**Sample Input**
```
  12.00
  20
  8
```

**Sample Output**
```
  15
```
## Day 3 - Day 3: Intro to Conditional Statements
**Task:** _Given an integer, , perform the following conditional actions:_

- If n is odd, print Weird
- If n is even and in the inclusive range of 2 to 5, print Not Weird
- If n is even and in the inclusive range of 6 to 20, print Weird
- If n is even and greater than 20, print Not Weird

**Input Format:** _A single line containing a positive integer, n._

**Output Format:** _Print Weird if the number is weird; otherwise, print Not Weird._

**Sample Input 0**
```
  3
```

**Sample Output 0**
```
  Weird
```
**Sample Input 1**
```
  24
```

**Sample Output 1**
```
  Not Weird
```
## Day 4 - Class vs. Instance
**Task:** _Write a Person class with an instance variable, age, and a constructor that takes an integer, initialAge, as a parameter. The constructor must assign initialAge to age after confirming the argument passed as initialAge is not negative; if a negative argument is passed as initialAge, the constructor should set age to 0 and print **Age is not valid, setting age to 0.**. In addition, you must write the following instance methods:_
  1. yearPasses() should increase the age instance variable by 1.
  2. amIOld() should perform the following conditional actions:
     - If age < 13, print **You are young.**.
     - If age >= 13 and age < 18, print **You are a teenager.**.
     - Otherwise, print **You are old.**.

**Input Format:** 
  _Input is handled for you by the stub code in the editor._
  _The first line contains an integer, T (the number of test cases), and the T subsequent lines each contain an integer denoting the age of a Person instance._

**Output Format:** _Complete the method definitions provided in the editor so they meet the specifications outlined above; If your methods are implemented correctly, each test case will print 2 or 3 lines (depending on whether or not a valid initialAge was passed to the constructor)._

**Sample Input**
```
  4
  -1
  10
  16
  18
```

**Sample Output**
```
  Age is not valid, setting age to 0.
  You are young.
  You are young.

  You are young.
  You are a teenager.

  You are a teenager.
  You are old.

  You are old.
  You are old.
```
## Day 5 - Loops

**Task:** _Given an integer, n, print its first 10 multiples. Each multiple n x i (where 1<= i >= 10) should be printed on a new line in the form: n x i = result._

**Input Format:** _A single integer, n._

**Output Format:** _Print 10 lines of output; each line i (where 1<= i >= 10) contains the result of n x i in the form:_
  - **n x i = result.**

**Sample Input**
```
  2
```

**Sample Output**
```
  2 x 1 = 2
  2 x 2 = 4
  2 x 3 = 6
  2 x 4 = 8
  2 x 5 = 10
  2 x 6 = 12
  2 x 7 = 14
  2 x 8 = 16
  2 x 9 = 18
  2 x 10 = 20
  
```
## Day 6 - Let's Review

**Task:** _Given a string, S, of length N that is indexed from 0 to N-1, print its even-indexed and odd-indexed characters as 2 space-separated strings on a single line (see the Sample below for more detail)._

**Input Format:** _The first line contains an integer, T (the number of test cases)._
_Each line i of the T subsequent lines contain a string, S._

**Output Format:** _For each String  S<sub>j</sub> (where 0 <= j<= T-1), print S<sub>j</sub> 's even-indexed characters, followed by a space, followed by S<sub>j</sub>'s odd-indexed characters._**

**Sample Input**
```
  2
  Hacker
  Rank
```

**Sample Output**
```
  Hce akr
  Rn ak
  
```
## Day 7 - Arrays

**Task:** _Given an array, A, of N integers, print A's elements in reverse order as a single line of space-separated numbers._

**Input Format:** _The first line contains an integer,  N(the size of our array).
The second line contains N space-separated integers that describe array A's_

**Output Format:** _Print the elements of array A in reverse order as a single line of space-separated numbers._**

**Sample Input**
```
  4
  1 4 3 2
```

**Sample Output**
```
  2 3 4 1
  
```
## Day 7 - Arrays

**Task:** _Given n names and phone numbers, assemble a phone book that maps friends' names to their respective phone numbers. You will then be given an unknown number of names to query your phone book for. For each name queried, print the associated entry from your phone book on a new line in the form name=phoneNumber; if an entry for name is not found, print Not found instead._

**Input Format:** _The first line contains an integer, n, denoting the number of entries in the phone book._
_Each of the n subsequent lines describes an entry in the form of n space-separated values on a single line. The first value is a friend's name, and the second value is an 8-digit phone number._

_After the n lines of phone book entries, there are an unknown number of lines of queries. Each line (query) contains a name to look up, and you must continue reading lines until there is no more input._

**Output Format:** _On a new line for each query, print Not found if the name has no corresponding entry in the phone book; otherwise, print the full **name** and **phonenumber** in the format name=phoneNumber._**

**Sample Input**
```
  3
  sam 99912222
  tom 11122222
  harry 12299933
  sam
  edward
  harry
```

**Sample Output**
```
  sam=99912222
  Not found
  harry=12299933
  
```
