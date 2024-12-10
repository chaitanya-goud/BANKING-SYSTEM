# BANKING-SYSTEM
## Project Description
A comprehensive Object-Oriented Programming (OOP) project that simulates a banking system. This application allows users to perform essential banking operations, providing a robust and secure environment to manage accounts, transactions, and user information.

## key note :
  there will be 2 parts of this file:
      1. focuses and explains on console based application(consoleapplication.)
      2. focuses and explains on gui based application

## console based application:
here is a youtube link explaining the console based application from scratch :
https://youtube.com/playlist?list=PLxCWTd5YqISA-Wjn3dcWRobFTkV_3vORa&si=w10pcI9FN4GpjEWe

We have seen the complete explaination of our UML daigram, code and demo.
We have introducted a new class called Customer.ai in our application
## CustomerAI Class
### Description:
The `CustomerAI` class introduces an intelligent assistant to enhance the user experience within the banking system. It leverages natural language processing (NLP) patterns to understand user queries and provide relevant responses. This class handles various banking operations through a conversational interface, ensuring seamless interaction.

### Key Features:
1. **Query Handling**:  
   Uses regex patterns to interpret user queries related to balance inquiries, deposits, withdrawals, account management, loan processing, and transaction history.

2. **Banking Operations**:  
   - View account balance.  
   - Deposit money into an account.  
   - Withdraw money from an account.  
   - View transaction history.  
   - Create and manage different types of accounts (savings, fixed, current).  
   - Manage loans, including creation, repayment, viewing, and closure.  

3. **Error Handling**:  
   Provides meaningful responses for invalid or unrecognized queries.

4. **User Interaction**:  
   Prompt-based interactions to request additional details (e.g., account number, deposit amount, loan details).

### Supported Queries:
Below are examples of supported queries grouped by functionality:

#### Balance Inquiry:
- "What is my balance?"  
- "How much money do I have in my account?"  
- "Show my current balance."

#### Deposits:
- "Deposit 5000 into my savings account."  
- "Add funds to my account."  
- "Credit 10000 to my account."

#### Withdrawals:
- "Withdraw 2000 from my current account."  
- "Take out money from my savings account."  
- "Debit 5000 from my account."

#### Transaction History:
- "Show my transaction history."  
- "List my account statement."  
- "View all transactions."

#### Account Management:
- "Create a new savings account."  
- "Open a fixed account with 5 years term."  
- "Show all my account details."

#### Loans:
- "Apply for a loan."  
- "Create a new loan for 50000 with a 7% interest rate."  
- "Repay 10000 for my loan."  
- "View all my loans."  
- "Close my loan account."

### Integration:
The `CustomerAI` class integrates seamlessly with the existing `Customer` and `Account` classes, using their methods to perform operations. It ensures encapsulation and reusability of code, adhering to OOP principles.

This class showcases the versatility and efficiency of combining OOP concepts with AI to deliver a robust banking solution.

## requirements
Here are the required libraries for your project:

java.util.ArrayList
java.util.List
java.util.Date
java.util.HashMap
java.util.Iterator
java.util.Scanner
java.lang.reflect.Field
java.util.HashSet
java.util.Set
java.util.regex.Pattern
java.util.Calendar

## files in the folder
Account.java
Bankingsystem23.java
BankStaff.java
CurrentAccount.java
Customer.java
CustomerAI.java
FixedAccount.java
Loan.java
Manager.java
SavingsAccount.java
Transaction.java
User.java

i guess we have explained each class in youtube and new customerai class above!
now lets see how to run the code(it as already been explained in demo)
javac Bankingsystem23.java
java Bankingsystem23

we are even attaching the class file so it must not be an issue!!

## note: 
we didnt use any database, we are storing all our data in the required data structures!

### below the link where we wanted to show how our ai assistant works :

##### Strengths:
##### Modular Query Handling: The system is easy to extend by adding new query patterns or actions.
##### Separation of Concerns: AI handles user interactions, while business logic is managed by the Customer class, promoting modularity.
##### Multiple Account Types: Supports various account types (e.g., savings, current), and can be extended.


