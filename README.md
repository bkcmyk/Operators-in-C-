# Implementation of Decision Making Statements in C++

## Objective

This project demonstrates the use of **decision-making statements** (`if`, `else`, `else if`, `switch`) in C++ through three beginner-friendly programs. Each program addresses a basic yet practical problem to help learners understand core programming logic and condition evaluation:

1. **Even or Odd Checker** – Checks whether a given number is even or odd using modulus operator.  
2. **Vowel or Consonant Checker** – Determines if an entered character is a vowel, consonant, or invalid input.  
3. **Month Name Selector** – Displays the name of the month based on user input using a switch-case structure.

---

## Program 1: Even or Odd Checker

### Logic

- Inputs: A single integer.  
- Uses the modulus operator `%` to check if the number is divisible by 2.  
- If divisible → even  
- Otherwise → odd

### Algorithm

1. Start  
2. Input a number  
3. If number % 2 == 0 → Print "Even"  
4. Else → Print "Odd"  
5. End  

### Sample Outputs
#### Sample 1:
Input: 
Enter a Number: 8

Output:
The number 8 is Even
#### Sample 2:
Input: 
Enter a Number: 5

Output:
The number 5 is Odd

---

##  Program 2: Vowel or Consonant Checker

###  Logic

- Inputs: A single character  
- Checks whether the input lies in `'A'-'Z'` or `'a'-'z'`  
- Then checks if the character is a vowel  
- If not vowel → consonant  
- If not a letter → invalid input

### Algorithm

1. Start  
2. Input a character  
3. If character is not an alphabet → Print "Invalid input"  
4. Else if character is a vowel → Print "Vowel"  
5. Else → Print "Consonant"  
6. End  

### Sample Outputs
#### Sample 1:
Input: 
Enter a Character: E

Output:
The Character entered E is a Vowel.

#### Sample 2:
Input: 
Enter a Character: x

Output:
The Character entered x is a Consonant.

#### Sample 3:
Input: 
Enter a Character: 5

Output:
Invalid input. Please enter an alphabet character.


---

## Program 3: Month Name Selector

### Logic

- Inputs: A number from 1 to 12  
- Uses a `switch` statement to print the corresponding month  
- Displays an error if the input is not between 1 and 12

### Algorithm

1. Start  
2. Display menu with month numbers (1–12)  
3. Input choice number  
4. Use switch-case:  
    - Case 1 → January  
    - Case 2 → February  
    - …  
    - Case 12 → December  
5. Default → Print "Invalid input"  
6. End  

### Sample Outputs
#### Sample 1:
Input: Enter Choice: 5

Output: May

#### Sample 2:
Input: Enter Choice: 11

Output: November

#### Sample 3:

Input: Enter Choice: 15

Output: Invalid Choice Entered. Please enter a number between 1 and 12.

---

## Learning Outcomes

This project enhances understanding of **conditional logic** and decision-making in C++. Through these programs, learners develop:

- Input validation using character and number ranges  
-  Control flow using `if`, `else`, `else if`, and `switch`  
-  Usage of logical and relational operators  
- Real-world problem-solving through decision-based logic  
- Clear, structured output formatting  

These types of exercises are essential for building programming confidence and foundational skills in C++.

