# college-finance
A company will be offering loans to students for the Fall 2023 semester and they’ve asked you to put together a program that facilitates the application process for loans.

Software Requirements
Students may apply for loans ranging from $1,000 to $10,000, which will be paid back over a 4-year period. Applications for the loans will be accepted from June 1 - August 15, 2023. The interest rate for the loan will depend on the student’s credit score and 2022 income according to the chart below. Students who meet the first criterion by having an excellent credit score will receive a prime lending rate, which is the best (lowest) available interest rate. Students who don’t meet the first criterion but meet one of the other criteria will receive a higher interest rate. Loans for students who do not meet any of the criteria will be denied.

Loans are typically disbursed (paid out) 21 days after the application date. However, for a fee of $30, express processing may be requested in which case the loan will be disbursed 3 days after the application date. The $30 fee will be added to the total loan amount, which will be used when determining whether the loan is approved and the interest rate.

Loans for students whose credit score is greater than or equal to 720, regardless of their 2022 income, will be approved with an interest rate of 7.5%.
Loans for students whose credit score is less than 720 and whose 2022 income is greater than or equal to 5 times the loan amount will be approved with an interest rate of 8.0%.
Loans for students who do not meet the first two criteria, but have a credit score of at least 500 and a 2022 income of at least 3 times the loan amount will be approved with an interest rate of 8.5%.
Loans for students who do not meet the first three criteria, but have a credit score of at least 350 and a 2022 income of at least 2 times the loan amount will be approved with an interest rate of 9.0%.
Loans for students who do not meet any of the criteria will be denied.

User Interface
It must display a header that lists the name of the application and provides instructions about using the program:
                 Welcome to College Finance!
 Applications for loans from $1000 to $10000 will be accepted from
June 1 to August 15, 2023. All loans will be paid back over a
4 year period. When prompted, please enter today's date, your credit
score, your 2022 income, and the loan amount. Loans are normally paid
out 21 days after the application date, but for a fee of $30, which
will be added to the loan amount, you may request Express Processing
in which case the loan will be paid out 3 days after the application
date. If your loan is approved, the loan amount, interest rate,
disbursement date, and monthly payment amount will be output. 

The user must be prompted for the following input values:
Date (month, day): Input as two integers, for example, 6 9.
Credit Score (300-850): Input as an integer.
2022 Income: Input as an integer.
Loan Amount (1000-10000): Input as an integer.
Express Processing (y, n): Input as a String. Any String that begins with ‘y’ or ‘Y’ is considered a “yes” response. Any String that does not begin with ‘y’ or ‘Y’ is a “no” response.
You may assume the year is 2023.

If the loan is approved, the program must then output the loan amount, interest rate, monthly payment, and the disbursement date in given format, for example:
Loan Amount: $3500.00
Interest Rate: 8.5%
Monthly Payment: $86.27
Disbursement Date: Tue, 8 15 2023

If the loan is not approved, the program must output “Loan denied”.

Input/Error Handling
If the user enters a date that is not between June 1 and August 15, inclusive, the program must output Invalid date. If the user enters a credit score that is not between 300 and 850, inclusive, the program must output Invalid credit score. If the user enters a negative income, the program must output Invalid income. If the user enters a loan amount that is not between 1000 and 10000, inclusive, the program must output Invalid loan amount. Your program must exit (stop) as soon as an invalid date, credit score, income, or loan amount is entered.

NOTE: You do not need to handle the situation where the user enters something other than an integer for month, day, credit score, income, or loan amount. We will learn to handle this later in the semester.
