# BANKING-SYSTEM
## Project Description
A comprehensive Object-Oriented Programming (OOP) project that simulates a banking system. This application allows users to perform essential banking operations, providing a robust and secure environment to manage accounts, transactions, and user information.

## Team Contribution :
- chaitanya :
  customerai.java,
  video editing,
  all the documentation(collab with shivaranjani and siddhartha),
  enchanced UML diagram (main lead),
  Bankingsystem23.java,
  idea of ai voice,
  gui.( As im kinda more into ai, so ai personality ai voice ai asisstant blah blah)
    
- siddhartha :
  bankaccount.java
  GUI(collab with sriram,chaitanya and shivaranjani) was main lead and giving instructions
  

- sriram:
 savings, fixed and current account code,
 gui


- pushpak:
 manager, bankstaff and loan account code,
 video presentations,gui.

- shivaranjani:
user, account classes code,
gui
video editing,
transaction.java.


## Concepts used :
- Abraction
- Polymorphism
- Inheritance
- Collections
- Encapulation

## key note :
  there will be 2 parts of this file:
      1. focuses and explains on console based application(ConsoleBasedApplication.zip)
      2. focuses and explains on gui based application
      3. WE FOCUSED ON DEVELOPMENT OF PROTOTYPE ONLY!!

## 1.Console based application:
from here on we'll be talikng about only console based application how it works etc etc as we wanted to go in a flow without directly jumping into the gui part!!!
## files in the folder
- Account.java
- Bankingsystem23.java
- BankStaff.java
- CurrentAccount.java
- Customer.java
- CustomerAI.java
- FixedAccount.java
- Loan.java
- Manager.java
- SavingsAccount.java
- Transaction.java
- User.java

## requirements
Here are the required libraries for your project:
- java.util.ArrayList
- java.util.List
- java.util.Date
- java.util.HashMap
- java.util.Iterator
- java.util.Scanner
- java.lang.reflect.Field
- java.util.HashSet
- java.util.Set
- java.util.regex.Pattern
- java.util.Calendar

### here is a youtube link explaining the console based application from scratch :
https://youtube.com/playlist?list=PLxCWTd5YqISA-Wjn3dcWRobFTkV_3vORa&si=w10pcI9FN4GpjEWe

We have seen the complete explaination of our UML daigram, code and demo.

### We have introducted a new class called Customer.ai in our application which isn't there in that link!
## CustomerAI Class
### Description:
The `CustomerAI` class introduces an intelligent assistant to enhance the user experience within the banking system. It leverages natural language processing (NLP) patterns to understand user queries and provide relevant responses. This class handles various banking operations through a conversational interface, ensuring seamless interaction.

### Key Features:
1. **Query Handling**:  
   Uses regex patterns to interpret user queries related to balance inquiries, deposits, withdrawals, account management, loan processing, and transaction history.

2. **Banking Operations**:  
   - View account balance.  
   - View transaction history.  
   - Create and manage different types of accounts (savings, fixed, current).  
   - Manage loans.  



### Supported Queries:
Below are examples of supported queries grouped by functionality:

#### Balance Inquiry:
- "What is my balance?"  
- "How much money do I have in my account?"  
- "Show my current balance."
  
#### Transaction History:
- "Show my transaction history."  
- "List my account statement."  
- "View all transactions."

#### Account Management:
- "Create a new savings account."  
- "Open a fixed account with 5 years term."  
- "Show all my account details."

and many more!!

### Integration:
The `CustomerAI` class integrates seamlessly with the existing `Customer` and `Account` classes, using their methods to perform operations. It ensures encapsulation and reusability of code, adhering to OOP principles.

This class showcases the versatility and efficiency of combining OOP concepts with AI to deliver a robust banking solution.

i guess we have explained each class in youtube and new customerai class above!
now lets see how to run the code(it as already been explained in demo)
javac Bankingsystem23.java
java Bankingsystem23

we are even attaching the class file so it must not be an issue!!

## note: 
we didnt use any database, we are storing all our data in the required data structures!

##### Strengths:
##### Modular Query Handling: The system is easy to extend by adding new query patterns or actions.
##### Separation of Concerns: AI handles user interactions, while business logic is managed by the Customer class, promoting modularity.
##### Multiple Account Types: Supports various account types (e.g., savings, current), and can be extended.

### Scalability Considerations
While the current implementation is designed as a prototype, it can be extended for larger systems with the following improvements:

##### Multi-User Support: The system should support multiple customers simultaneously, using secure session management to track and manage individual users.

##### Dynamic Account and Loan Handling: The design can be extended to dynamically manage different account and loan types, possibly integrating with a database for scalable data management.

##### Enhanced NLP Capabilities: The current regex-based query handling can be replaced or augmented with more advanced NLP techniques or models (e.g., OpenNLP, Dialogflow) to improve understanding of complex user queries.

##### Concurrency Management: For multi-user support, the system must implement proper concurrency handling to avoid issues in a distributed environment.

### link for demo for Customer.ai class which is explained by chaitanya
https://youtu.be/LsdmPjgzsgw

### link for explanation for updated loan class
https://youtu.be/COIZL5Gr-x8?si=TiGuxW1zqlQCQRhu

### conclusion :
The CustomerAI class offers a basic prototype of a banking AI assistant capable of handling a range of user queries and banking operations. While it serves as a proof of concept, future improvements in scalability, security, and NLP capabilities will be essential to support a production-level banking system. By addressing these areas, the system can evolve into a robust, secure, and user-friendly solution for managing banking interactions through AI.
### so, this is all about Customerai.java and console based application, lets proceed futher!!!!

# GUI (2ND PHASE)

So, in this phase we gotta a new class called BankingSystemGUI
## BankingSystemGUI.java file 
this file is graphical user interface of the project that we are working and it uses all the methods and classes and runs the user interface 

for the complete explanation of the code of BankingSystemGUI.java watch the following video which is explained by siddhartha :
https://www.youtube.com/watch?v=1d_gtGBKdRA

### we have also made a demo video for the implementation of GUI interface 
which is explained is explained by shivaranjani
https://youtu.be/TVYvadY-fsw?si=sFgBvLT6v3j7q1Tw
