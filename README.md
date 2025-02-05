# Bookstore Management System

## Overview
The **Bookstore Management System** is a Java-based console application that allows users to manage a bookstore. It includes features such as adding, updating, and removing books, customer account creation, order placement, order history viewing, and new arrival book listings.

## Features
- **Book Management**: Add, update, remove, and list books.
- **Customer Management**: Create customer accounts and store their information.
- **Order Management**: Place book orders and view order history.
- **New Arrivals**: View newly added books.
- **Error Handling**: Ensures smooth user experience with input validation.

## Technologies Used
- Java (Core Java, OOP Concepts)
- Collections Framework (ArrayList)
- Exception Handling
- Scanner for User Input

## How to Run
### Prerequisites
- Java Development Kit (JDK) installed
- Any Java IDE (e.g., IntelliJ, Eclipse) or a terminal with `javac` and `java` commands

### Steps
1. Clone the repository or copy the source code.
2. Open the project in an IDE or a text editor.
3. Compile the program using the command:
   ```sh
   javac BookstoreManagementSystem.java
   ```
4. Run the program:
   ```sh
   java BookstoreManagementSystem
   ```

## Usage
Once the program starts, users can interact through a menu-driven system:
1. **Add a Book** - Enter book details like title, author, price, ISBN, published year, and new arrival status.
2. **Update a Book** - Modify book details using its ISBN.
3. **Remove a Book** - Delete a book by entering its ISBN.
4. **View All Books** - Display all available books in the store.
5. **Create Customer Account** - Register a new customer with their name and email.
6. **Place an Order** - Order a book by entering ISBN and quantity.
7. **View Order History** - Check all previous orders of a customer.
8. **View New Arrivals** - List all recently added books.
9. **Exit** - Quit the application.

## Example Interaction
```
Bookstore Management System
1. Add Book
2. Update Book
3. Remove Book
4. Print All Books
5. Create Customer Account
6. Place Order
7. View Order History
8. View New Arrival Books
9. Exit
Enter your choice: 1
Enter Book Title: Java Programming
Enter Author: John Doe
Enter Price: $49.99
Enter ISBN: 123456789
Enter Published Year: 2022
Enter if new arrival (true/false): true
Book added successfully!
```

## Future Enhancements
- Implement a graphical user interface (GUI) for better usability.
- Integrate database support for persistent storage.
- Add search and filtering options for books.
- Enable online payment integration.

## License
This project is licensed under the MIT License.

## Author
Developed by Shikhar Panchal

