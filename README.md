#This code was written for an assignment in the MIT Open Course Ware class 
#Introduction To Computer Science And Programming In Python 6.0001

# House Hunting Python Program

This Python program helps you determine how long it will take to save enough money for a down payment on a house, based on certain assumptions. There are two parts to the program: Part A and Part B.

## Part A: House Hunting

In Part A, we assume the following:
1. `total_cost`: The cost of your dream home.
2. `portion_down_payment`: The portion of the cost needed for a down payment (assumed to be 25% or 0.25).
3. `current_savings`: The amount of money you have saved so far (initially $0).
4. `r`: The annual return on your investments (assumed to be 4% or 0.04).
5. `annual_salary`: Your annual salary.
6. `portion_saved`: The portion of your monthly salary that you dedicate to saving (in decimal form).

The program asks the user to enter the following variables:
1. The starting annual salary (`annual_salary`).
2. The percentage of the salary to be saved each month (`portion_saved`).
3. The cost of your dream home (`total_cost`).

The program then calculates the number of months it will take to save up enough money for the down payment and displays the result.

## Part B: Saving, with a raise

In Part B, we extend Part A by considering salary raises. We assume the same variables as in Part A, with an additional variable:
1. `semi_annual_raise`: The semi-annual salary raise (in decimal form).

The program asks the user to enter the following variables:
1. The starting annual salary (`annual_salary`).
2. The percentage of the salary to be saved each month (`portion_saved`).
3. The cost of your dream home (`total_cost`).
4. The semi-annual raise (`semi_annual_raise`).

The program calculates the number of months it will take to save up enough money for the down payment, considering the salary raises every six months, and displays the result.

## How to Use the Program

1. Run the program.
2. Follow the prompts and enter the required information as requested.
3. After entering all the information, the program will calculate the number of months required to save enough money for the down payment.
4. The program will display the result in the format "Number of months: [months]".

Please ensure that the input values are entered correctly to obtain accurate results.

## Example Test Cases

### Part A Test Cases

Test Case 1:
```
Enter your annual salary: 120000
Enter the percent of your salary to save, as a decimal: 0.10
Enter the cost of your dream home: 1000000
Number of months: 183
```

Test Case 2:
```
Enter your annual salary: 80000
Enter the percent of your salary to save, as a decimal: 0.15
Enter the cost of your dream home: 500000
Number of months: 105
```

### Part B Test Cases

Test Case 1:
```
Enter your starting annual salary: 120000
Enter the percent of your salary to save, as a decimal: 0.05
Enter the cost of your dream home: 500000
Enter the semi-annual raise, as a decimal: 0.03
Number of months: 142
```

Test Case 2:
```
Enter your starting annual salary: 80000
Enter the percent of your salary to save, as a decimal: 0.10
Enter the cost of your dream home: 800000
Enter the semi-annual raise, as a decimal: 0.
