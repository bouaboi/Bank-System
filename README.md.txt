Features:


- Manage Clients: Add, delete, update, or find client records.



- Transactions: Deposit or withdraw money with balance checks.

- View Data: Display all clients, individual details, or total balances.

- Save Data: Stores client info in Clients.txt for future use.

- Easy Menus: Navigate with clear, interactive console menus.

- Manage Users (New): Add, delete, update, or find user accounts with specific permissions.

- Login System (New): Secure login for users with credential checks.

- Logout Function (New): Replaces the traditional "Exit" option with user logout.

- Permissions System (New): Control user access based on assigned permissions.

---

Usage:

Start the program to see the Main Menu:

- Show Client List

- Add New Client

- Delete Client

- Update Client Info

- Find Client

- Transactions

- Manage Users (New)

- Logout (New)

Type a number (1–8) to choose an option.

In the Transactions Menu, select:

- Deposit

- Withdraw

- Total Balances

- Main Menu

In the Manage Users Menu (New), select:

- Show Users List

- Add New User

- Delete User

- Update User Info

- Find User

- Return to Main Menu

Follow prompts to enter client details (e.g., account number, name) or transaction amounts.

---

Data saves :

Client data saves automatically to Clients.txt.

User data saves automatically to Users.txt

---

Notes:

- Ensure Clients.txt and Users.txt are writable in the program’s folder.

- Data format in Clients.txt:
AccountNumber#//#PinCode#//#Name#//#Phone#//#Balance

- Data format in Users.txt (New):
Username#//#Password#//#Permissions

- Example for Clients.txt:
A001#//#1234#//#John Doe#//#1234567890#//#1000.50

- Example for Users.txt:
admin#//#1234#//#-1

- Non-Windows users may need to replace system("cls") with system("clear").