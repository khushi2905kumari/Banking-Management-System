
 ![title](https://user-images.githubusercontent.com/112396675/200484557-167382b4-aa38-4d1d-aa12-ba1dd2eaae59.png)

# Banking Management System
This is a C++ based web application designed for banking purposes. The application is built using object-oriented programming principles and allows users to perform various banking tasks such as depositing and withdrawing money from their accounts, creating and deleting accounts, and checking their bank statements and balances.

# Getting Started
To run the application, you will need to have a C++ compiler installed on your system. 
- Clone the repository to your local machine and compile the source code using the command:
 
       git clone https://github.com/khushi2905kumari/Banking-Management-System.git
                    
- Open terminall & copy paste this command ⬇️

       g++ -o main main.cpp account.cpp transaction.cpp
   
- Once compiled, run the application using the command:

      ./main
   
# Usage
Upon starting the application, the user is presented with a menu of available options:

- Create account
- Delete account 
- Deposit
- Withdraw
- Balance inquiry
- Bank statement
- Exit

           #Opening an Account
![OpeningAccount](https://user-images.githubusercontent.com/112396675/200481817-ac4525fb-66a4-4a29-b190-b36e30f72485.png)

The user can select the desired option and follow the prompts to complete the transaction.

# Backend Storage
The application uses a file-based storage system to store user account and transaction data. The file, <b>banking.data</b> , contains a list of all user accounts and their corresponding transaction history. Whenever a user performs a transaction, the data is written to the file to ensure that it is persisted across sessions.

           #Storing Details into a Separate File
![DATABASE](https://user-images.githubusercontent.com/112396675/200481894-308383e5-5bdf-43b0-8b6f-a9751c4dc867.png)


# Features
- Users can create new accounts and delete existing ones.
- Users can deposit money into their accounts and withdraw money from them.
- The application keeps a record of all transactions made by each user.
- Users can view their account balance and transaction history.

# Design
The application is designed using object-oriented programming principles to ensure code modularity, reusability, and maintainability. The code is structured into classes such as **Account**, **Transaction**, and User to separate concerns and improve code readability. The use of encapsulation, inheritance, and polymorphism ensures that the code is flexible and extensible.

# Future Improvements
The application can be improved in several ways, such as:

- Adding a login system to enhance security and ensure that only authorized users can access their accounts
- Adding support for multiple currencies
- Integrating with external payment gateways
- Improving the user interface to make it more user-friendly
- Implementing additional layers of authentication and authorization to enhance the security of the application.

<i>If you have any suggestions or improvements to these future plans, feel free to submit a pull request or contribute to the project.</i>


# Thank You 🤍
Follow for more! ©️
