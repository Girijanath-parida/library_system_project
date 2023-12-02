# library_system_project
Library inventory project

This is a Python program that implements a basic library system called "Treasure of books library." The program allows users to perform various operations such as adding books, modifying quantities, deleting books, and displaying the remaining books. It also allows users to view available books, borrow books, and return books. The book details are stored in a file called library.txt.

Usage
1.	Make sure you have Python installed on your system.
2.	Download or clone the repository to your local machine.
3.	Open a terminal or command prompt and navigate to the directory where the code is located.
4.	Run the program by executing the following command:
5.	The program will display a menu with options to perform different operations.
6.	Enter the corresponding number for the desired operation and follow the prompts.

Features
1. Add a Book - 
This option allows you to add a book to the library. You will be prompted to enter the name of the book and its quantity. The book details will be stored in a file named library.txt.

2. Modify Quantity - 
This option allows you to modify the quantity of a book in the library. You will be prompted to enter the name of the book and the new quantity. The program will update the quantity of the book in the library.txt file.

3. Delete a Book - 
This option allows you to delete a book from the library. You will be prompted to enter the name of the book. The program will remove the book from the library.txt file.

4. Show Remaining Books - 
This option displays the remaining books in the library along with their quantities. The program reads the book details from the library.txt file and prints them on the screen.

5. Borrow - Allows users to borrow a book by specifying the book name and quantity to borrow. Updates the quantity of the book in the library.

6. Return - Allows users to return a book by specifying the book name and quantity to return. Updates the quantity of the book in the library.
7. Exit - 
Selecting this option will exit the program.

File Structure

library.py: The main Python script that implements the library management system.
library.txt: The text file that stores the book details (name and quantity) in a comma-separated format.
temp.txt: A temporary file used for updating the book quantities.


