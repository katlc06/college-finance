Test ID: test8.5InterestNotExpressDisbursementAug15

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header
  
    Month Day (e.g., 6 9): 7 25
    Credit Score (300-850): 675
    2022 Income: 15000
    Loan Amount (1000-10000): 3500
    Express Processing(y,n): n
Expected Results:
    
    Loan Amount: $3500.00
    Interest Rate: 8.5%
    Monthly Payment: $86.27
    Disbursement Date: Tue, 8 15 2023

    Program Exits
Actual Results:
   
    Loan Amount: $3500.00
    Interest Rate: 8.5%
    Monthly Payment: $86.27
    Disbursement Date: Tue, 8 15 2023

    Program Exits
--------------------------------------
Test ID: test7.5InterestRateExpressProcessingDisbursementJuly2
   
Author: katlc06

Description:
   
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 6 29
    Credit Score (300-850): 825
    2022 Income: 4000
    Loan Amount (1000-10000): 9500
    Express Processing(y,n): yeah
Expected Results:
    
    Loan Amount: $9530.00
    Interest Rate: 7.5%
    Monthly Payment: $230.42
    Disbursement Date: Sun, 7 2 2023

    Program Exits
Actual Results:
    
    Loan Amount: $9530.00
    Interest Rate: 7.5%
    Monthly Payment: $230.42
    Disbursement Date: Sun, 7 2 2023

    Program Exits
--------------------------------------
Test ID: testLoanDeniedCredit675IncomeTooLow

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header
    
    Month Day (e.g., 6 9): 7 20
    Credit Score (300-850): 675
    2022 Income: 4515
    Loan Amount (1000-10000): 3600
    Express Processing(y,n): abc
Expected Results:

    Loan denied
    
    Program Exits
Actual Results:

    Loan denied
    
    Program Exits
--------------------------------------
Test ID: testExpressProcessingIncreasesInterestRate

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 7 25
    Credit Score (300-850): 675
    2022 Income: 17500
    Loan Amount (1000-10000): 3500
    Express Processing(y,n): Y
Expected Results:

    Loan Amount: $3530.00
    Interest Rate: 8.5%
    Monthly Payment: $87.01
    Disbursement Date: Fri, 7 28 2023

    Program Exits
Actual Results:

    Loan Amount: $3530.00
    Interest Rate: 8.5%
    Monthly Payment: $87.01
    Disbursement Date: Fri, 7 28 2023

    Program Exits
--------------------------------------
Test ID: testInvalidDateJunNearEndofMonthBoundary
    
Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header
    
    Month Day (e.g., 6 9): 6 31
Expected Results:
   
   Invalid date

    Program Exits
Actual Results:
   
    Invalid date

    Program Exits
--------------------------------------
Test ID: testInvalidCreditScoreTooLow

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 7 31
    Credit Score (300-850): 250
Expected Results:
    
    Invalid credit score

    Program Exits
Actual Results:
    
    Invalid credit score

    Program Exits
--------------------------------------
Test ID: testNegativeIncome

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 8 3
    Credit Score (300-850): 567
    2022 Income: -4
Expected Results:
    
    Invalid income

    Program Exits
Actual Results:
    
    Invalid income

    Program Exits
--------------------------------------
Test ID: testInvalidLoanAmountTooLow

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 8 15
    Credit Score (300-850): 760
    2022 Income: 10025
    Loan Amount (1000-10000): 999
Expected Results:
    
    Invalid loan amount

    Program Exits
Actual Results:
    
    Invalid loan amount

    Program Exits
--------------------------------------
Test ID: testInvalidLoanAmountTooHigh

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 7 10
    Credit Score (300 - 850): 720
    2022 Income: 14000
    Loan Amount (1000-10000): 11000
Expected Results:
    
    Invalid loan amount

    Program Exits
Actual Results:
    
    Invalid loan amount

    Program Exits
--------------------------------------
Test ID: testInvalidCreditScoreTooHigh

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header
    
    Month Day (e.g., 6 9): 8 4
    Credit Score (300 - 850): 900
Expected Results:
    
    Invalid credit score
    
    Program Exits
Actual Results:
    
    Invalid credit score
    
    Program Exits
--------------------------------------
Test ID: testInvalidDateJuly32

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 7 32
Expected Results:
    
    Invalid date
    
    Program Exits
Actual Results:
    
    Invalid date
    
    Program Exits
--------------------------------------
Test ID: testInvalidDateAug16

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 8 16
Expected Results:
    
    Invalid date
    
    Program Exits
Actual Results:
    
    Invalid date
    
    Program Exits
--------------------------------------
Test ID: testInvalidDateMay

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header
    
    Month Day (e.g., 6 9): 5 4
Expected Results:
    
    Invalid date
    
    Program Exits
Actual Results:
    
    Invalid date
    
    Program Exits
--------------------------------------
Test ID: testInvalidDateJuly0

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header
    
    Month Day (e.g., 6 9): 7 0
Expected Results:
    
    Invalid date
    
    Program Exits
Actual Results:
    
    Invalid date
    
    Program Exits
--------------------------------------
Test ID: testLoanDeniedCreditTooLowIncome3TimesLoan

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 7 10
    Credit Score (300 - 850): 320
    2022 Income: 3000
    Loan Amount (1000-10000): 1000
    Express Processing(y,n): n
Expected Results:
    
    Loan denied

    Program Exits
Actual Results:
    
    Loan denied

    Program Exits
--------------------------------------
Test ID: test9.0InteresCredit350ExpressProcessingDisbursementJuly15

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 7 12
    Credit Score (300 - 850): 350
    2022 Income: 4000
    Loan Amount (1000-10000): 1000
    Express Processing(y,n): Y
Expected Results:
    
    Loan Amount: $1030.00
    Interest Rate: 9.0%
    Monthly Payment: $25.63
    Disbursement Date: Sat, 7 15 2023

    Program Exits
Actual Results:
    
    Loan Amount: $1030.00
    Interest Rate: 9.0%
    Monthly Payment: $25.63
    Disbursement Date: Sat, 7 15 2023

    Program Exits
--------------------------------------
Test ID: test8.0InterestNotExpressProcessingDisbursementSep2

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 8 12
    Credit Score (300 - 850): 650
    2022 Income: 6000
    Loan Amount (1000-10000): 1000
    Express Processing(y,n): n
Expected Results:
    
    Loan Amount: $1000.00
    Interest Rate: 8.0%
    Monthly Payment: $24.41
    Disbursement Date: Sat, 9 2 2023

    Program Exits
Actual Results:
    
    Loan Amount: $1000.00
    Interest Rate: 8.0%
    Monthly Payment: $24.41
    Disbursement Date: Sat, 9 2 2023

    Program Exits
--------------------------------------
Test ID: test9.0InterestCredit500ExpressProcessingDisbursementJuly15

Author: katlc06

Description:
    
    Preconditions: WolfpackFinance program started
    Header

    Month Day (e.g., 6 9): 7 12
    Credit Score (300 - 850): 500
    2022 Income: 4500
    Loan Amount (1000-10000): 2000
    Express Processing(y,n): Y
Expected Results:
    
    Loan Amount: $2030.00
    Interest Rate: 9.0%
    Monthly Payment: $50.52
    Disbursement Date: Sat, 7 15 2023
    
    Program Exits
Actual Results:
    
    Loan Amount: $2030.00
    Interest Rate: 9.0%
    Monthly Payment: $50.52
    Disbursement Date: Sat, 7 15 2023
    
    Program Exits
--------------------------------------
