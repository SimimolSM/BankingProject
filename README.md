# BankingProject
SIMPLE BANKING SYSTEM
Banking system plays an important role in modern economic world. This project is a simple banking system that implements the features of a real-time banking system. Features include: 
 Open a new account 
 Withdraw 
 Deposit 
 Check Balance 
 Statement 
 Display All 
 Delete Account 
Some additional features are included while creating a new account, like phone number validation and date validation. This system is implemented with the help of OOP’s concept. It is completed with the help of two classes and an interface. The actual flow of the program starts by assigning values to the class. That data is stored in an array of object of class Account. Each time an operation is called it checks for the account number in that array of the class. Only if  the condition is true it  proceeds further. Otherwise, it pops a message.
The project starts with a message asking the user to input records. That input is stored in an array of object of class Account. The object of class Account is created with the instance of interface AccountInterface, that implements complete abstraction. Each time user selects an option, it invokes the specific method from Account class. This project uses Pattern and Matcher classes of Java to validate the date and phone number. The user can continue with their choice until they choose exit option.
