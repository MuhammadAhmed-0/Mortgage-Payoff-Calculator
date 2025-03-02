# Mortgage Payoff Calculator

A simple and interactive **Mortgage Payoff Calculator** that helps users calculate the following based on their mortgage loan details:
- Monthly payment
- Total interest paid
- New loan payoff time when extra payments are applied

This tool allows users to input the loan amount, interest rate, loan term, and any extra monthly payments to see how they can pay off their mortgage faster and save on interest.

## Features
- **Currency Selector**: Users can select a currency for the calculation (USD, EUR, GBP, etc.).
- **Input Fields**: Users enter their loan details:
  - Loan Amount
  - Interest Rate
  - Loan Term (years)
  - Extra Payment (optional)
- **Results**: The calculator shows the following results:
  - Monthly payment
  - Total interest paid over the life of the loan
  - New payoff time with extra payments applied
- **Responsive Design**: The page adjusts for various screen sizes, ensuring usability on mobile and desktop devices.

## How It Works
1. **Loan Input**: Users input the loan amount, interest rate, loan term, and optional extra monthly payments.
2. **Mortgage Formula**: The monthly payment is calculated using the standard mortgage payment formula:
   \[
   M = P \times \frac{r(1+r)^n}{(1+r)^n-1}
   \]
   where:
   - \( M \) is the monthly payment
   - \( P \) is the loan principal
   - \( r \) is the monthly interest rate
   - \( n \) is the total number of payments (loan term * 12)
3. **Extra Payment Impact**: The calculator calculates the new loan term and the total interest paid when extra payments are applied.


## How to Use
1. Clone or download the repository.
2. Open the `index.html` file in a browser.
3. Fill in the fields for **Loan Amount**, **Interest Rate**, **Loan Term**, and **Extra Payment** (if any).
4. Click **Calculate** to see the results (Monthly Payment, Total Interest, and New Payoff Time).

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mortgage-payoff-calculator.git
