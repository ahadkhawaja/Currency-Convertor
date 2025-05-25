Title: Currency Converter in C++
Introduction
The currency converter program is designed to convert an entered amount from one currency to another, using fixed exchange rates. It allows users to select between four major currencies — USD, EUR, GBP, and PKR — and facilitates real-time conversion. The program emphasizes user-friendly interaction, input validation, and formatted output. It also ensures flexibility in user inputs by allowing case-insensitive currency codes and repeated conversions.
Objective
The primary objective of this project is to develop a robust and user-friendly currency converter that delivers accurate results, ensures a seamless user experience, and handles input gracefully.
Features Implemented
Supported Currencies:
The program supports the following currencies:
•	USD (United States Dollar)
•	EUR (Euro)
•	GBP (British Pound)
•	PKR (Pakistani Rupee)
Case-Insensitive Input:
Users can enter currency codes in any letter case (e.g., usd, Usd, USD), and the program will automatically convert them to uppercase to ensure accurate processing.
Input Validation:
The program checks:
•	If the entered currency codes are valid and on the supported list.
•	If a conversion between the given currencies is possible.
•	If the amount entered is a valid, positive number.
Repeated Conversion Prompt:
After each conversion, the user is asked whether they would like to perform another conversion. This provides a continuous and user-friendly loop without requiring the program to restart manually.
Clear User Instructions:
The console displays:
•	Welcome message
•	List of supported currencies
•	Format of expected inputs
Formatted Output:
The conversion result is displayed with exactly two decimal places, ensuring clarity and financial precision.
Program Workflow
1.	Step 1: Display a welcome message and a list of supported currencies.
2.	Step 2: Prompt the user to enter:
o	Source currency code
o	Target currency code
o	Amount to be converted
3.	Step 3: Convert all currency codes to uppercase to allow case-insensitive comparison.
4.	Step 4: Validate all inputs to ensure correctness.
5.	Step 5: Perform the currency conversion using pre-defined exchange rates.
6.	Step 6: Display the result in a clean and formatted output.
7.	Step 7: Ask the user whether they want to perform another conversion and repeat if necessary.
Conclusion
This currency converter project demonstrates fundamental concepts of C++ programming, including:
•	Control structures
•	Input/output handling
•	String manipulation
•	Loops and conditional logic
•	Data formatting
It is an ideal beginner-to-intermediate level application that prioritizes clean design, robust functionality, and excellent usability. The additional features such as case-insensitive input and repeated conversions, enhance the program’s interactivity and make it more user-friendly.
![Uploading image.png…]()
