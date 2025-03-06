# Bank-Management-system-in-Assembly-Language

The Bank Management System is a simple program created using Assembly language. It allows users to log in using a username and password, and then perform basic banking tasks like checking their balance, depositing money, and withdrawing money. The program provides a menu for users to choose what action they want to do.
In this project, the user needs to enter their username and password correctly to access their account. Once logged in, they can check their balance, deposit money, withdraw money (if they have enough funds), and exit the system. The program also ensures that the entered password is hidden by displaying * instead of the actual characters for security.

Main Functionalities
The Bank Management System provides the following key features:

1.	User Login:
o	The program asks the user to enter a username and password. It checks whether the entered credentials match the stored usernames and passwords (abc/SZABIST for user1, xyz/PASS123 for user2).
o	If the username or password is wrong, the user is asked to try again.

3.	Banking Menu:
o	After the user logs in successfully, a menu is displayed with the following options:
1.	Check Balance: Shows the current balance (starting at 500).
2.	Deposit: Lets the user deposit money into their account, increasing their balance.
3.	Withdraw: Lets the user withdraw money from their account. If they don’t have enough funds, the program shows an error message.
4.	Exit: Allows the user to exit the program.
   
3.	Password Input:
o	When the user enters their password, it is hidden by showing * for each character typed, to keep the password safe.

5.	Input Validation:
o	The program checks that the user selects a valid option from the menu. If an invalid choice is made, the program asks the user to try again.
o	When the user tries to withdraw money, the program checks if they have enough balance. If not, it shows an error message.

6.	Continue or Exit:
o	After completing any action, the program asks the user if they want to continue with another operation or exit. The user can choose to continue by pressing c or exit by pressing e.

This simple banking system shows how Assembly language can be used for basic user interactions, security, and handling different banking operations.


