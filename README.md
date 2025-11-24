# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.  
# Date : 24/11/2025
# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
# Output:
# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Date : 
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
   
### Step 5:  
  Use `printf()` to display the values of `PI` and `DAYS`.     
### Step 6:  
  Stop
# Program:
# Output:
# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Date : 
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside main(), declare and initialize variables of types int, float, double, and char.
### Step 4: 
   Display their values using printf().
### Step 5:    
   Stop
# Program:
# Output:
# Result: 

# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Date : 
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
# Output:
# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Date : 
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:Skip to main content
SEC
SEC
TT Module - I
Started on	Friday, 22 November 2024, 2:27 PM
State	Finished
Completed on	Friday, 22 November 2024, 2:38 PM
Time taken	11 mins 19 secs
Grade	100.00 out of 100.00
Question 1
Correct
Mark 20.00 out of 20.00
Not flaggedFlag question
Question text
Write a C program to swap two numbers without using third variable.


For example:

Input	Result
100 200
Numbers before swapping: 100 200
Numbers after swapping: 200 100
Answer:(penalty regime: 0 %)
Reset answer
Ace editor not ready. Perhaps reload page?
Falling back to raw text area.
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d%d",&a,&b);
    printf("Numbers before swapping: %d %d\n",a,b);
    printf("Numbers after swapping: %d %d",b,a);
}
Feedback
Input	Expected	Got	
100 200
Numbers before swapping: 100 200
Numbers after swapping: 200 100
Numbers before swapping: 100 200
Numbers after swapping: 200 100
-200 -900
Numbers before swapping: -200 -900
Numbers after swapping: -900 -200
Numbers before swapping: -200 -900
Numbers after swapping: -900 -200
0 1
Numbers before swapping: 0 1
Numbers after swapping: 1 0
Numbers before swapping: 0 1
Numbers after swapping: 1 0
Passed all tests!  

Correct
Marks for this submission: 20.00/20.00.
Question 2
Correct
Mark 20.00 out of 20.00
Not flaggedFlag question
Question text
Write a C program to read the student marks and print the which class he/she got?

marks>=70 print FIRST CLASS WITH DISTINCTION

60>= marks <70 print FIRST CLASS

50>= marks <60 print SECOND CLASS

40>= marks <50 print THIRD CLASS

marks<40 print U r Failed...Better luck next time
For example:

Input	Result
70
...FIRST CLASS WITH DISTINCTION...
62                                                                          
  
...FIRST CLASS...
Answer:(penalty regime: 0 %)
Reset answer
Ace editor not ready. Perhaps reload page?
Falling back to raw text area.
#include <stdio.h>
int main()  
{
    int a;
    scanf("%d",&a);
    if (a>=70)
        printf("...FIRST CLASS WITH DISTINCTION...");
    if (a>=60 && a<70)
        printf("...FIRST CLASS...");
    if (a>=50 && a<60)
        printf("...SECOND CLASS...");
    if (a>=40 && a<50)
        printf("...THIRD CLASS...");
    if(a<40)
        printf("...U r Failed...Better luck next time");
    return 0;
}
Feedback
Input	Expected	Got	
70
...FIRST CLASS WITH DISTINCTION...
...FIRST CLASS WITH DISTINCTION...
62
...FIRST CLASS...
...FIRST CLASS...
58
...SECOND CLASS...
...SECOND CLASS...
45
...THIRD CLASS...
...THIRD CLASS...
39
...U r Failed...Better luck next time
...U r Failed...Better luck next time
55
...SECOND CLASS...
...SECOND CLASS...
70
...FIRST CLASS WITH DISTINCTION...
...FIRST CLASS WITH DISTINCTION...
90
...FIRST CLASS WITH DISTINCTION...
...FIRST CLASS WITH DISTINCTION...
Passed all tests!  

Correct
Marks for this submission: 20.00/20.00.
Question 3
Correct
Mark 20.00 out of 20.00
Not flaggedFlag question
Question text
write a program to find distance traveled by the car based on speed and time?

For example:

Input	Result
100 4

distance:400.00 km
Answer:(penalty regime: 0 %)
Reset answer
Ace editor not ready. Perhaps reload page?
Falling back to raw text area.
#include<stdio.h>
int main()
{
    float a,b;
    scanf("%f %f",&a,&b);
    printf("distance:%.2f km",a*b);
    
}
Feedback
Input	Expected	Got	
100 4
distance:400.00 km
distance:400.00 km
90.87 6.7
distance:608.83 km
distance:608.83 km
Passed all tests!  

Correct
Marks for this submission: 20.00/20.00.
Question 4
Correct
Mark 20.00 out of 20.00
Not flaggedFlag question
Question text
Write a C Program to print the ASCII value of vowels (A,E,I,O,U) using the switch statement (EX. A-65, E-69)

For example:

Input	Result
A
65
Answer:(penalty regime: 0 %)
Ace editor not ready. Perhaps reload page?
Falling back to raw text area.
#include <stdio.h>
int main()
{
    char a;
    scanf("%c",&a);
    if(a=='A'||a=='E'||a=='U')
        printf("%d",a);
    else
        printf("The Character is not vowel");
}
Feedback
Input	Expected	Got	
A
65
65
U
85
85
B
The Character is not vowel
The Character is not vowel
Passed all tests!  

Correct
Marks for this submission: 20.00/20.00.
Question 5
Correct
Mark 20.00 out of 20.00
Not flaggedFlag question
Question text
Write a C Program to check the eligibility for college admission if their condition and norms get satisfied using nested if statement. Should satisfy

1. if age above 18 and marks above 60 then it displays "He/She is eligible for college admission"

2. if age above 18 and marks below 60 then it displays "Obtained marks less than 60"

3. if age is below 18 then it displays "Age less than 18"


For example:

Input	Result
21 50
Obtained marks less than 60
16 70
Age less than 18
18 65
He/She is eligible for college admission
Answer:(penalty regime: 0 %)
Ace editor not ready. Perhaps reload page?
Falling back to raw text area.
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d%d",&a,&b);
    if (a>=18){
        if(b>=60){
            printf("He/She is eligible for college admission");
        }
        else
            printf("Obtained marks less than 60");
    }
    else
        printf("Age less than 18");
}
Feedback
Input	Expected	Got	
21 50
Obtained marks less than 60
Obtained marks less than 60
16 70
Age less than 18
Age less than 18
18 65
He/She is eligible for college admission
He/She is eligible for college admission
Passed all tests!  

Correct
Marks for this submission: 20.00/20.00.
Finish review
Skip <span id="mod_quiz_navblock_title">Quiz navigation</span>
Quiz navigation
Question1This pageQuestion2This pageQuestion3This pageQuestion4This pageQuestion5This page
Show one page at a time
Finish review

# Output:
[exp 1 c programming.pdf](https://github.com/user-attachments/files/23729072/exp.1.c.programming.pdf)

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


