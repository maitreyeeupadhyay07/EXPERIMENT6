MAITREYEE UPADHYAY 25070123071

AIM : TO STUDY OF CONDITIONAL STATEMENTS IN PYTHON

Theory:
Conditional statements in Python are used to make decisions based on certain conditions. They control the flow of execution of a program.
Python provides the following decision-making statements:
-if statement – Executes a block of code if a condition is true.
-if-else statement – Executes one block if the condition is true and another block if it is false.
-if-elif-else ladder – Checks multiple conditions and executes the matching block.

Conditions are formed using:
-Comparison operators: >, <, ==, !=, >=, <=
-Logical operators: and, or, not

Conditional statements help in solving real-world problems like checking even/odd numbers, grading systems, salary calculation, tax calculation, leap year checking, etc.

Thus, conditional statements allow a program to take decisions and execute appropriate actions based on given conditions.

ALGORITHM:

6A: Check Whether a Number is Positive, Negative or Zero
1. Start
2. Input a number `num`
3. If `num > 0`, print "Positive"
4. Else if `num == 0`, print "Zero"
5. Else print "Negative"
6. Stop

6B: Check Whether a Number is Even or Odd
1. Start
2. Input a number `num`
3. If `num % 2 == 0`, print "Even"
4. Else print "Odd"
5. Stop

6C: Find the Largest of Three Numbers
1. Start
2. Input three numbers `a`, `b`, and `c`
3. If `a >= b` and `a >= c`, print `a` as largest
4. Else if `b >= a` and `b >= c`, print `b` as largest
5. Else print `c` as largest
6. Stop

6D: Calculate Grade Based on Marks
1. Start
2. Input marks
3. If marks ≥ 90, print Grade A
4. Else if marks ≥ 80, print Grade B
5. Else if marks ≥ 70, print Grade C
6. Else if marks ≥ 60, print Grade D
7. Else print Grade F
8. Stop

6E: Check Whether a Year is a Leap Year
1. Start
2. Input year
3. If year is divisible by 4 and not divisible by 100
   OR divisible by 400
   → Print "Leap Year"
4. Else print "Not a Leap Year"
5. Stop

6F. Gross Salary Calculation
1. Start
2. Input basic salary
3. If basic ≤ 10000 → HRA = 20% of basic, DA = 80% of basic
4. Else if basic ≤ 20000 → HRA = 25% of basic, DA = 90% of basic
5. Else → HRA = 30% of basic, DA = 95% of basic
6. Calculate Gross = Basic + HRA + DA
7. Display Gross Salary
8. Stop

6G. Income Tax Calculation
1. Start
2. Input annual income
3. If income ≤ 2,50,000 → Tax = 0
4. Else if income ≤ 5,00,000 → Tax = 5% of (income − 2,50,000)
5. Else if income ≤ 10,00,000 → Tax = 5% of 2,50,000 + 20% of (income − 5,00,000)
6. Else → Tax = 5% of 2,50,000 + 20% of 5,00,000 + 30% of (income − 10,00,000)
7. Display Income Tax
8. Stop

6H. Check Vowel or Consonant
1. Start
2. Input a letter
3. Check if the letter is in (a, e, i, o, u)
4. If yes → Print "Vowel"
5. Else → Print "Consonant"
6. Stop

6I. Date Validation and Increment
1. Start
2. Input date in dd/mm/yyyy format
3. Split date into day (dd), month (mm), year (yy)
4. Determine maximum days in the month
5. Check if date is valid
6. If day is last day of month → Set day = 1 and increment month
7. If month is December and day is 31 → Set day = 1, month = 1, increment year
8. Else → Increment day by 1
9. Display incremented date
10. Stop



Conclusion:

The programs were successfully implemented using Python decision-making statements.
The experiment helped in understanding how conditional statements work and how they control the execution flow of a program.

Hence, the objectives of the experiment were achieved successfully.
