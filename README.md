🏧 ATM Machine System
📘 Project Overview

The ATM Machine System is a simulation of a real-world Automated Teller Machine (ATM). It allows users to perform basic banking operations such as balance inquiry, cash withdrawal, deposit, and PIN management. The project demonstrates the core functionality and workflow of an ATM system using software engineering principles and UML use case modeling.

👤 Author

Name: Taha Khalid
SID: 65963

🎯 Objective

The main objective of this project is to design and implement a functional model of an ATM Machine using a Use Case Diagram to represent the system’s interaction between the User (Customer) and the Bank Server.

⚙️ Key Features (from the Use Case Diagram)

The ATM Machine System allows users to:

Insert ATM Card – The user inserts the card to start a transaction.

Enter PIN – The system verifies the entered PIN for authentication.

Select Transaction Type – The user chooses between multiple operations:

Balance Inquiry

Cash Withdrawal

Cash Deposit

PIN Change

Mini Statement

Process Transaction – The system communicates with the bank database to complete the requested action.

Eject Card – The card is ejected, and the user session ends.

🧩 Use Case Diagram

The use case diagram represents the interaction between:

Actor: Customer (User)

System: ATM Machine

External System: Bank Server (for verification and transaction processing)

Includes Relationships:

“Enter PIN” is included in all transaction types.

“Process Transaction” is included in all financial operations.

Extends Relationships:

“Print Receipt” extends from “Cash Withdrawal,” “Cash Deposit,” and “Mini Statement.”

“Error Message” extends from “Enter PIN” when invalid credentials are entered.

🏗️ System Flow Summary

The customer inserts their card.

The system requests a PIN.

Upon validation, the user can choose the desired operation.

The system communicates with the bank server for transaction execution.

The transaction completes, the card is ejected, and a receipt may be printed.

💡 Tools & Technologies Used

Modeling Tool: StarUML / Visual Paradigm / Lucidchart

Programming Language (optional): C++ / Java / Python (depending on implementation)

Diagram Type: UML Use Case Diagram

🧠 Learning Outcome

Understanding of UML use case modeling.

Clarity on system–actor interactions.

Visualization of system functionality before implementation.

📄 License

This project is created for academic and educational purposes by Taha Khalid.
