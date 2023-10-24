# Banking Exercise

Create a banking system fulfilling the requirements specified below.

## Requirements

- A **bank** has a **name**
- A **bank** has many **accounts**
- **Transactions** are stored on the **accounts**.
- There are different types of **accounts**: **savings** and **checking**.
- **Checking accounts** can have multiple types, **money market** and **individual**.
- **Individual accounts** can't withdraw more than $1000 at a time.
- An **account holder** must be able to **deposit**, **withdraw**, **transfer** and print a **statement**(date, amount, balance) funds.
- The statement should have filters (deposits, withdrawals, date)

Statement example
-----------------
Given a client makes a deposit of 1000 on 10-01-2012  
And a deposit of 2000 on 13-01-2012  
And a withdrawal of 500 on 14-01-2012  
When she prints her bank statement  
Then she would see  

date       || credit   || debit    || balance  
14/01/2012 ||          || 500.00   || 2500.00   
13/01/2012 || 2000.00  ||          || 3000.00  
10/01/2012 || 1000.00  ||          || 1000.00

Your solution must have tests.