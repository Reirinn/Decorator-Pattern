# Decorator-Pattern
CIMB is a digital bank that offers GSave and UpSave savings accounts. As with a typical Savings Account, it contains accountNumber, accountName, and a balance for that account.

The typical savings account offers an interest rate of 1%. The benefits of the typical savings account is the same with the "Standard Savings Account" as compared to other banks.

The GSave account offers an interest rate of 2.5%. Benefits include the "Standard Savings Account" plus access to "GCash transfer".

The UpSave account offers the highest interest rate of 4.0%. Benefits include the "Standard Savings Account" plus "with Insurance".

Develop a decorator pattern approach that will implement the given UML diagram

The content of your Cimb.java should ONLY contain the following codes with the exception of inserting your own package name :

![image](https://github.com/Reirinn/Decorator-Pattern/assets/142465054/e100310b-41fa-4954-abf3-7be7ae39d155)


You should display the following output:

![image](https://github.com/Reirinn/Decorator-Pattern/assets/142465054/4e8a9002-0846-4861-a659-bf084e398543)


Description of the following methods

showAccountType() - Either returns "Savings Account", "GSave" or "UpSave"
getInterestRate() - Either returns 1% for Savings Account; 2.5% for GSave; 4.0% UpSave
getBalance() - Returns the balance of the account set.
showBenefits() - Either returns "Standard Savings Account" for Savings Account; benefits offered by savings account + "GSave Transfer"; benefits offered by savings account + "With Insurance";
computeBalanceWithInterest() - returns new balance by computing the balance plus the interest depending on the interest rate.
showInfo() - Returns details of account number, account name, and balance.
BankAcountDecorator must be an interface.

Follow instructions. You are not allowed to insert other methods except what is stated in the diagram (setters and getters are allowed).

In your solution you must provide the following in your Github link account:

• Problem statement (description of the problem. Just copy what is stated here.

• UML Class Diagram

• Uploaded java codes for the solution.

# Class Diagram

![image](https://github.com/Reirinn/Decorator-Pattern/assets/142465054/f7ac07bd-7514-4815-9cc6-87b4a89817c8)
