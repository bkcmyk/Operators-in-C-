Use of Operators in C++


Objective:

This project showcases the use of conditional statements (if, else if, else) in C++ through three beginner-friendly programs. Each program solves a practical problem to reinforce core programming concepts:
1. Grade Calculator – Calculates the average of five subject scores and assigns a grade.
2. Coordinate Locator – Determines the location of a point in a 2D Cartesian plane.
3. Number Sign Checker – Checks whether a given number is positive, negative, or zero.
   
Program 1: Grade Calculator

Logic:

• Inputs: Marks in Maths, Chemistry, Physics, English, and Biology.

• The program computes the average score.

• It then assigns a grade based on the following scale:

  <img width="299" height="199" alt="image" src="https://github.com/user-attachments/assets/7d6d1492-f7bf-40c4-abab-600eca773f23" />

Algorithm:

1. Start
2. Input marks for Maths, Chemistry, Physics, English, and Biology
3. Calculate average = (Maths + Chemistry + Physics + English + Biology) / 5
4. If average ≥ 90 → Grade = 'O'
5. Else if average ≥ 80 → Grade = 'A'
6. Else if average ≥ 70 → Grade = 'B'
7. Else if average ≥ 60 → Grade = 'C'
8. Else if average ≥ 50 → Grade = 'D'
9. Else → Grade = 'FAIL'
10. Display the grade
11. End

Sample Output:
Input:
Enter Maths score: 75
Enter Chemistry score: 85
Enter Physics score: 98
Enter English score: 90
Enter Biology score: 75

Output:
Average Score: 84
Grade: A



Program 2: Coordinate Locator

Logic:
Given a point (x, y), the program determines its position in the Cartesian plane using the following rules:

<img width="345" height="214" alt="image" src="https://github.com/user-attachments/assets/d3c96903-6fe6-4ed6-8393-9f9aa6b15b6e" />

Algorithm: 

1. Start
2. Input x and y coordinates
3. If x > 0 and y > 0 → Print "1st Quadrant"
4. Else if x < 0 and y > 0 → Print "2nd Quadrant"
5. Else if x < 0 and y < 0 → Print "3rd Quadrant"
6. Else if x > 0 and y < 0 → Print "4th Quadrant"
7. Else if x == 0 and y ≠ 0 → Print "On Y-axis"
8. Else if x ≠ 0 and y == 0 → Print "On X-axis"
9. Else → Print "At Origin"
10. End

Sample Output: 

•	Input:
Enter x coordinate: -6
Enter y coordinate: 1

Output:
The point is in the 2nd Quadrant

•	Input:
Enter x coordinate: -6
Enter y coordinate: 1

Output:
The point is in the 2nd Quadrant

•	Input:
Enter x coordinate: 0
Enter y coordinate: -7

Output:
The point is on the Y-axis


•	Input:
Enter x coordinate: 0
Enter y coordinate: 0

Output:
The point is at the Origin


Program 3: Number Sign Checker

Logic:
This program checks whether a given integer is positive, negative, or equal to zero, using simple conditional checks:

 <img width="489" height="111" alt="image" src="https://github.com/user-attachments/assets/a07c0299-9820-4753-9b45-36635f42b8de" />

Algorithm:

1. Start
2. Input a number
3. If number > 0 → Print "Positive"
4. Else if number < 0 → Print "Negative"
5. Else → Print "Equal to Zero"
6. End

   
Sample Output:

•	Input:
Enter an integer: -5

Output:
The number is negative

•	Input:
Enter an integer: 0

Output:
The number is equal to 0

•	Input:
Enter an integer: 25

Output:
The number is positive


Learning Outcomes: 
This combined project strengthens the understanding of decision-making in C++. These problems are essential practice for anyone starting with programming fundamentals, especially focusing on:

• User input handling
• Decision logic
• Output formatting
• Logical thinking
• Real-world problem solving using code

