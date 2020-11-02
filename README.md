# CS19B032_ATMProject_CaseStudy2
There are Three important Classes

They are Main , Account , TransactionEntry

There is Main class that performs the actions that customer wants to do.

And there is class named Account which has the data of the Customer (name , account number ,pin balance ,transaction history and it has methods to perform required activities like Withdraw, Deposit , Change Pin ...

and There is class Named TransactionEntry that Saves the data of Transactions of Customers.

I have used Encapsulation in this Case Study

1. Main Class :

    I have taken example of 10 Accounts.
    
    It asks the Customer Account number , if it is a valid Number then it asks Pin. After Pin Validation it lists some actions Shown below         that a Customer wants.
    1. Deposit 
    2. Withdraw
    3. Fast Cash
    4. Display Transaction
    5. Current Balance
    6. Change Pin
    7. Cancel Transaction
    
    For each action a method is Created in Account Class

    For each action performed by Customer will be Stored By TransactionEntry Class. The data will be Sent through Account Class.

2.Account Class :

  It has following Methods

  First transaction of the Customer while creating Account
    1.Method to deposit Money
    2.Method to withdraw Money
    3.Method to Change Pin
    4.Method to Change Pin
    5.Methods to Acesss private Vrilables like Account Number ,Name , Pin, Current Balance

    Mainly it has The Amount of Funds present in the ATM.

3.TransactionEntry Class :

    It has two Methods namely addEntry and displayEntry

    1.addEntry Method saves the data of Every action performed by the Customer.
    2.displayEntry Method Displays The Every action performed by the Customer.
    
ThankYou
