# Loan-Repayment-Calculator
> This project, a loan repayment calculator, is one of my very first python projects I have completed at the University of Iowa. It calculates your minimum monthly payment based on how much you owe and total years until full repayment. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Variables](#variables)
* [Usage](#usage)
* [Project Status](#project-status)
* [Areas for Improvement](#areas-for-improvement)





## General Information
- This code allows the user to see how many years/months it will take in order to pay back loans. It accounts for interest, amount borrowed, and goal time period of repayment.
- I made this project so I could calculate how long it would take me to pay back all my loans...the results were unfavorable to say the least.
-Code uses input variables and an interactive program for users to calculate their exact repayments.


## Technologies Used
- Spyder Desktop, Version 3.8


## Variables
List of input variables/calculations (code):
- years = int(input("Number of years:"))
- loan_per_year = float(input("loan_per_year:"))
- interest_rate = float(input("interest_rate:"))
- total_int = (loan_per_year + total_owed) * interest_rate
- total_owed = total_owed + total_int + loan_per_year
- monthly_payment = float(input("monthly payment:" ))
- monthly_int_rate = interest_rate/12
- minimum_monthly_payment = total_owed *monthly_int_rate


## Usage
If you were to run the code:
First, it will ask inputs for number of years loan was taken out for (i.e 4 years of college), loan per year, and interest rate. After amounts are defined, it will then print total owed at graduation. 
Next, it will ask for monthly payment amount you are willing/planning to spend per month. If the monthly payment is less than the minimum monthly payment, an error statement will pop up. 
Otherwise, code then calculates minimum monthly payment, months, and years to pay off your loans.

Example Output:
`Number of years:4

loan_per_year:13000

interest_rate:0.05
total owed at graduation
$ 58833

monthly payment:400
A monthly payment of $ 400.0 will work.
The minimum monthly payment for this loan would be $245
it will take 227 months to pay off your student loans.
it will take 18.92 years to pay off your student loans.`


## Project Status
Project is: complete


## Areas for Improvement
Since this project was done before COVID, it does not account for the period of no interest on loans thus I would not be able to get the exact amount I owe. To improve this code, I would have to add an if/else statement or another mathematical calculation to account for the gap of no interest.
