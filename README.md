# Decision-Making-Statements-in-C-Plus-Plus

## Overview
This project demonstrates the use of **decision-making statements** in C++.  
These statements are used to control the flow of a program based on certain conditions.  
They allow the program to make choices and take different actions based on user input or logical checks.

---

## Theory
Decision-making statements are a fundamental part of C++ programming.  
They help in making the program behave differently under different conditions.  
These include:

1. **if Statement**  
   Executes a block of code only if a given condition is true.

2. **if-else Statement**  
   Runs one block if the condition is true, and another if it's false.

3. **else-if Ladder**  
   Used when multiple conditions need to be checked one after another.

4. **Nested if**  
   An if condition inside another if. Used when one condition depends on another.

5. **switch-case**  
   Best for fixed options (like menu choices or operator-based programs). Compares a variable with several constant cases and executes the matching one.

---

## Summary of the Programs

1. **Even or Odd Checker**  
   Checks if a number is divisible by 2. Uses the modulus operator and if-else condition to determine and display whether the number is even or odd.

   ## Overview
   This program accepts an integer from the user and determines whether it is **even** or **odd**.  
   It uses the **modulus operator** (`%`) and **if-else** decision-making to perform the check.

---

   ## Theory
   A number is:
   - **Even** if it is divisible by 2 (remainder is 0).
   - **Odd** if it is not divisible by 2 (remainder is 1).

   **Key C++ Concepts Used:**
   1. **Integer Input (`int`)** – Stores the number entered by the user.
   2. **Modulus Operator (`%`)** – Returns the remainder after division.
   3. **if-else Statement** – Executes different code depending on the remainder.

---

   ## Algorithm
   1. **Start** the program.
   2. Include the input-output stream header file: `#include <iostream>`.
   3. Use the standard namespace: `using namespace std;`.
   4. Declare an integer variable `num`.
   5. Prompt the user to enter any number and store it in `num`.
   6. Use the modulus operator to check divisibility by 2:
   - If `num % 2 == 0`, display that the number is even.
   - Else, display that the number is odd.
   7. **End** the program.


2. **Vowel or Consonant Identifier**  
   Accepts a character input and checks whether it's a vowel using either if-else or a switch case.  
   If not a vowel, it’s treated as a consonant.## Overview
   This program takes a single alphabet character from the user and determines whether it is a **vowel** or a **consonant**.  
   It uses **decision-making statements** (`if-else`) along with the **logical OR operator** to check multiple conditions.

---

   ## Theory
   In English, the vowels are: **a, e, i, o, u** (both uppercase and lowercase).  
   All other alphabets are considered consonants.

   **Key C++ Concepts Used:**
   1. **Character Input (`char`)** – Stores a single character entered by the user.
   2. **Logical OR (`||`) Operator** – Used to check if the entered character matches any vowel.
   3. **if-else Statement** – Executes different blocks of code based on the condition.
   4. **Case Sensitivity** – Both uppercase and lowercase vowels are checked.

---

   ## Algorithm
   1. **Start** the program.
   2. Include the input-output stream header file: `#include <iostream>`.
   3. Use the standard namespace: `using namespace std;`.
   4. Declare a character variable `alphabet`.
   5. Prompt the user to enter an alphabet and store it in `alphabet`.
   6. Use an `if` statement to check if `alphabet` matches any of the vowels:
   - Lowercase: `a`, `e`, `i`, `o`, `u`
   - Uppercase: `A`, `E`, `I`, `O`, `U`
   7. If it matches, display `"The given alphabet is a vowel"`.
   8. Else, display `"The given alphabet is a consonant"`.
   9. **End** the program.

   

3. **Largest of Three Numbers**  
   Takes three numbers and uses else-if ladder or nested if to compare and determine the largest among them.

   ## Overview
   This program takes three integers as input from the user and determines which one is the **largest**.  
   It uses **if-else-if** decision-making along with **logical AND (`&&`)** operators to compare the numbers.

---

   ## Theory
   To find the largest number among three:
   - Compare the first number with the other two.
   - If it’s greater than both, it’s the largest.
   - Else, compare the second number with the remaining one.
   - If neither of the first two is the largest, the third number is the largest.

   **Key C++ Concepts Used:**
   1. **Integer Input (`int`)** – Stores the numbers entered by the user.
   2. **Logical AND Operator (`&&`)** – Used to check multiple conditions simultaneously.
   3. **if-else-if Statement** – Allows checking multiple conditions in sequence.

---

   ## Algorithm
   1. **Start** the program.
   2. Include the input-output stream header file: `#include <iostream>`.
   3. Use the standard namespace: `using namespace std;`.
   4. Declare three integer variables: `a`, `b`, `c`.
   5. Prompt the user to enter the first number and store it in `a`.
   6. Prompt the user to enter the second number and store it in `b`.
   7. Prompt the user to enter the third number and store it in `c`.
   8. Use `if` statements to compare:
   - If `a > b` **and** `a > c`, `a` is the largest.
   - Else if `b > a` **and** `b > c`, `b` is the largest.
   - Else, `c` is the largest.
   9. Display the largest number.
   10. **End** the program.

4. **Simple Calculator**  
   Implements a calculator using a switch statement.  
   Based on the operator entered (`+`, `-`, `*`, `/`), it performs the respective arithmetic operation.

   ## Overview
   This program implements a basic calculator that performs **addition**, **subtraction**, **multiplication**, and **division** based on the operator entered by the user.  
   It uses the **switch-case** statement for cleaner handling of multiple constant choices.

---

   ## Theory
   A **switch-case** statement allows the program to execute one block of code among many options based on the value of a variable.  
   This makes it ideal for menu-driven programs like calculators.

   **Key C++ Concepts Used:**
   1. **Character Input (`char`)** – Stores the operator (`+`, `-`, `*`, `/`) entered by the user.
   2. **Floating-point Numbers (`float`)** – Used to store operands for decimal precision.
   3. **switch-case Statement** – Executes a specific block depending on the entered operator.
   4. **break Statement** – Ends a case to prevent "fall-through" into the next case.
   5. **default Case** – Handles invalid operator inputs.

---

   ## Algorithm
   1. **Start** the program.
   2. Include the input-output stream header file: `#include <iostream>`.
   3. Use the standard namespace: `using namespace std;`.
   4. Declare a `char` variable `oper` for the operator.
   5. Declare two `float` variables `num1` and `num2` for operands.
   6. Prompt the user to enter an operator (`+`, `-`, `*`, `/`) and store it in `oper`.
   7. Prompt the user to enter the first number and store it in `num1`.
   8. Prompt the user to enter the second number and store it in `num2`.
   9. Use a `switch` statement:
   - **Case '+':** Add `num1` and `num2` and display the result.
   - **Case '-':** Subtract `num2` from `num1` and display the result.
   - **Case '*':** Multiply `num1` and `num2` and display the result.
   - **Case '/':** Divide `num1` by `num2` and display the result.
   - **default:** Display an error message for invalid operators.
   10. **End** the program.

5. **Switch Case with Break Statements (Profession Selector)**  
   A menu-driven application using switch-case. Displays professions based on the user's numeric choice.  
   A default message is shown for invalid selections.

   ## Overview
   This program allows the user to select a profession from a predefined menu.  
   Based on the numeric choice entered, it displays the corresponding profession.  
   If the user enters an invalid option, a default message is shown.

---

   ## Theory
   A **switch-case** statement is ideal for menu-driven applications where multiple constant values need to be compared.  
   Each **case** corresponds to one possible option, and the **default** case handles any input that doesn't match.

   **Key C++ Concepts Used:**
   1. **Integer Input (`int`)** – Stores the user’s numeric choice.
   2. **switch-case Statement** – Executes different code based on the user's choice.
   3. **break Statement** – Ensures control exits the switch after a matching case is executed.
   4. **default Case** – Displays a message for invalid selections.

---

   ## Algorithm
   1. **Start** the program.
   2. Include the input-output stream header file: `#include <iostream>`.
   3. Use the standard namespace: `using namespace std;`.
   4. Declare an integer variable `choice`.
   5. Display the menu:
   Dancer
   Engineer
   Doctor   
   Singer
   Housewife
   Others
   6. Prompt the user to enter their choice and store it in `choice`.
   7. Use a `switch` statement:
   - **Case 1:** Display `"Dancer"`.
   - **Case 2:** Display `"Engineer"`.
   - **Case 3:** Display `"Doctor"`.
   - **Case 4:** Display `"Singer"`.
   - **Case 5:** Display `"Housewife"`.
   - **Case 6:** Display `"Others"`.
   - **default:** Display `"The choice you have selected is not valid"`.
   8. **End** the program.

---

## Conclusion
Decision-making statements are vital in building logical and interactive C++ programs.  
This project demonstrates how to:
- Use **if**, **if-else**, and **if-else-if** for checking conditions.
- Use **switch** for cleaner handling of multiple constant choices.

Understanding these concepts lays the groundwork for more advanced topics like **loops**, **functions**, and **algorithms**.
