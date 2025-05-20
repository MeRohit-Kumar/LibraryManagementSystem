# LibraryManagementSystem
This is a console-based Library Management System written in Python. It allows users to perform basic library operations such as listing available books, borrowing and returning books, and donating new books. The system also tracks which student has issued which book.

🔧 Features
📖 View a list of available books

📥 Borrow books with student name tracking

📤 Return books (only if issued)

🎁 Donate new books to the library

📋 Track all currently borrowed books

🚪 Exit the system with a clean message

🧑‍💻 Technologies Used
Language: Python 3

IDE: VSCode / PyCharm / Any Python-supported editor

▶️ How to Run
Clone or download this repository:

bash
Copy
Edit
git clone https://github.com/your-username/library-management-system.git
Navigate to the project directory:

bash
Copy
Edit
cd library-management-system
Run the Python script:

bash
Copy
Edit
python library.py
📌 Code Structure
Library class: Handles book listing, borrowing, returning, and donation

Student class: Handles user input for book-related actions

track list: Keeps track of issued books along with student names

Console loop: Menu-based interface for interaction

📝 Example Interaction
plaintext
Copy
Edit
WELCOME TO MyLibrary

CHOOSE WHAT YOU WANT TO DO:-
1. Listing all books
2. Borrow books
3. Return books
4. Donate books
5. Track books
6. Exit the library

Enter your choice: 1
6 AVAILABLE BOOKS ARE:
 ♦-- DBMS
 ♦-- Python Basics
 ...

