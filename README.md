# LoopsAndConditionsInPython
1. Write a program that calculates and displays a person’s body mass index (BMI). The BMI is often used to determine whether a person with a sedentary lifestyle is overweight or underweight for his or her height.
A person’s BMI is calculated with the following formula: BMI = weight × 703 / height2
where weight is measured in pounds and height is measured in inches. The program should display a message indicating whether the person has optimal weight, is underweight, or is overweight. A sedentary person’s weight is considered to be optimal if his or her BMI is between 18.5 and 25. If the BMI is less than 18.5, the person is considered to be underweight. If the BMI value is greater than 25, the person is considered to be overweight.

2. Write a program that asks the user to enter a number of seconds.
	? There are 60 seconds in a minute. If the number of seconds entered by the user is greater than or equal to 60, the program should display the number of minutes in that many seconds.
	? There are 3,600 seconds in an hour. If the number of seconds entered by the user is greater than or equal to 3,600, the program should display the number of hours in that many seconds.
	? There are 86,400 seconds in a day. If the number of seconds entered by the user is greater than or equal to 86,400, the program should display the number of days in that many seconds.

3. Write a program that takes coordinates (x, y) of a center of a circle and its radius from the user, the program will determine whether a point lies inside the circle, on the circle or outside the circle.

4. A software company sells a package that retails for PKR 99. Quantity discounts are given according to the following table.
Write a program that asks for the number of units sold and computes the total cost of the purchase. Input Validation: Make sure the number of units is greater than 0.Write a program that takes a character from the user and determines whether the character entered is a capital letter, a small case letter, a digit or a special symbol.

5. Write a program that displays the following menu:
Geometry Calculator
	1. Calculate the Area of a Circle
	2. Calculate the Area of a Rectangle
	3. Calculate the Area of a Triangle
	4. Quit
Enter your choice (1-4):
	If the user enters 1, the program should ask for the radius of the circle and then display its area. Use the following formula: area = pr2 Use 3.14159 for p and the radius of the circle for r.
	If the user enters 2, the program should ask for the length and width of the rectangle and then display the rectangle’s area. Use the following formula: area = length * width
	If the user enters 3 the program should ask for the length of the triangle’s base and its height, and then display its area. Use the following formula: area = base * height * .5
	If the user enters 4, the program should end.
Input Validation: Display an error message if the user enters a number outside the range of 1 through 4 when selecting an item from the menu. Do not accept negative values for the circle’s radius, the rectangle’s length or width, or the triangle’s base or height.

6. A long-distance carrier charges the following rates for telephone calls:
Quantity
Discount
10–19
20%
20–49
30%
50–99
40%
100 or more
50%
Starting Time of Call
Rate per Minute
00:00–06:59
0.12 PKR
07:00–19:00
0.55 PKR
19:01–23:59
0.35 PKR
Write a program that asks for the starting time and the number of minutes of the call, and displays the charges. The program should ask for the time to be entered as a floating point number in the form HH.MM. For example, 07:00 hours will be entered as 07.00, and 16:28 hours will be entered as 16.28. Input Validation: The program should not accept times that are greater than 23:59. Also, no number whose last two digits are greater than 59 should be accepted.

7. Write a program that takes one value from the user and asks about the type of conversion and then performs a conversion depending on the type of conversion. If user enters: ? I -> convert from inches to centimeters. ? G -> convert from gallons to liters. ? M -> convert from mile to kilometer. ? P -> convert from pound to kilogram.

8. An Internet service provider has three different subscription packages for its customers:
? Package A: For PKR 995 per month 10 hours of access are provided. Additional hours are PKR2.00 per hour.
? Package B: For PKR104.95 per month 20 hours of access are provided. Additional hours are PKR1.00 per hour.
? Package C: For PKR 700.95 per month unlimited access is provided.
Write a program that calculates a customer’s monthly bill. It should ask which package the customer has purchased and how many hours were used. It should then display the total amount due. Input Validation: Be sure the user only selects package A, B, or C. Also, the number of hours used in a month cannot exceed 744 (Hours in 31 days)
It should also displays how much money Package A customers would save if they purchased packages B or C, and how much money Package B customers would save if they purchased Package C. If there would be no savings, no message should be printed. 

9. In a company, worker efficiency is determined on the basis of the time required for a worker to complete a specific job. If the time taken by the worker is between 2 - 3 hours, then the worker is said to be highly efficient. If the time required by the worker is 3 - 4 hours, then the worker is ordered to increase their speed.
 If the time taken is 4 - 5 hours then the worker is given training to improve his speed and if the time taken by the worker is more than 5 hours then the worker must leave the company. If the time taken by the worker is input through the keyboard then find the efficiency of the worker.

10. The colors red, blue, and yellow are known as the primary colors because they cannot be made by mixing other colors. When you mix two primary colors, you get a secondary color, as shown here:
? When you mix red and blue, you get purple.
? When you mix red and yellow, you get orange.
? When you mix blue and yellow, you get green.
Design a program that prompts the user to enter the names of two primary colors to mix. If the user enters anything other than “red,” “blue,” or “yellow,” the program should display an error message. Otherwise, the program should display the name of the secondary color that results.

11. Write a code that takes two integers as input representing a month and day and prints the season for that month and day. Assume that months are specified as an integer between 1 and 12 (1 for January, 2 for February, and so on) and that the day of the month is a number between 1 and 31.
 If the date falls between 16/12 and 15/3, you should print "Winter". 
If the date falls between 16/3 and 15/6, you should print "Spring". If the date falls between 16/6 and 15/9, you should print "Summer". And if the date falls between 16/9 and 15/12, you should print "Fall".

12. Mr. Books Booksellers has a book club that awards points to its customers based on the number of books purchased each month. The points are awarded as follows:
? If a customer purchases 0 books, he or she earns 0 points.
? If a customer purchases 1 book, he or she earns 5 points.
? If a customer purchases 2 books, he or she earns 15 points.
? If a customer purchases 3 books, he or she earns 30 points.
? If a customer purchases 4 or more books, he or she earns 60 points.
Design a program that asks the user to enter the number of books that he or she has purchased this month and displays the number of points awarded.

 13. Write a Python program that reads a date from the user in numeric form. For example, February 17, 2003 would be entered as the three integers 2, 17, and 2003.
 Your program must then determine if the date is a “valid” date. Use the following information to determine if the date is valid: January, March, May, July, August, October, and December all have 31 days. April, June, September, and November all have 30 days. February has 28 days in a non-leap year and 29 days in a leap year.
 Print either “valid date” or “invalid date” as output. Note: Algorithm for identifying leap year is:
 • If the year is evenly divisible by 4, go to step 2. Otherwise, go to step 5.
 • If the year is evenly divisible by 100, go to step 3. Otherwise, go to step 4.
 • If the year is evenly divisible by 400, go to step 4. Otherwise, go to step 5.
 • The year is a leap year (it has 366 days). • The year is not a leap year (it has 365 days).