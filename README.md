# Mortgage Amortization with Extra Payment

This notebook calculates a mortgage amortization schedule with the option to make an extra payment in a specific month. It visualizes the mortgage's principal payments, interest payments, and remaining balance over time.

## Features
- Calculate monthly mortgage payments based on principal, annual interest rate, and loan term.
- Allow an extra payment in any chosen month to reduce the remaining balance faster.
- Generate amortization schedules showing principal, interest payments, and balance.
- Plot the principal and interest payments over time and the remaining mortgage balance.

## How to Use
1. **Modify the Parameters:**
   You can modify the following input parameters to fit your mortgage scenario:
   - `principal`: The initial loan amount (e.g., $720,000).
   - `annual_interest_rate`: The annual interest rate in percent (e.g., 3.625%).
   - `years`: The loan term in years (e.g., 30 years).
   - `extra_payment_month`: The month in which you wish to make an extra payment (e.g., month 45).
   - `extra_payment_amount`: The amount of extra payment (e.g., $20,000).
   - `start_date`: The starting date of the loan.

2. **Run the Notebook:**
   - The notebook will compute the monthly payments, interest payments, and remaining balance.
   - If you choose to make an extra payment in a particular month, it will adjust the schedule accordingly.
   
3. **Visualizations:**
   - Principal and interest payments over time.
   - Remaining mortgage balance over time.

## Output
- The notebook outputs a detailed amortization schedule with the following fields:
  - `Date`: The date of each payment.
  - `Month Paid`: The current payment month.
  - `Month Remaining`: The number of months left to pay off the loan.
  - `Principal Payment`: The portion of the payment applied to the principal.
  - `Interest Payment`: The portion of the payment applied to interest.
  - `Balance`: The remaining loan balance after the payment.

- Two visualizations:
  1. Principal and Interest Payments Over Time.
  2. Remaining Mortgage Balance Over Time.

## Dependencies
Make sure to install the following Python libraries before running the notebook:
```bash
pip install numpy pandas matplotlib
