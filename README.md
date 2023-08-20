# Library Management System

This repository contains a menu-driven program for a Library Management System implemented as a Python application. The program allows users to manage the information of books in a library, including printing book information, searching for books, adding new books, removing books, borrowing books, and returning books. The program stores book information in "booksInfo.txt" and borrowed book information in "borrowedInfo.txt".

## Features

- **Print books information:** Display information for all books in the library, including serial number, title, number of authors, price, and total number of copies (available in the library + borrowed).

- **Search a book:** Search for a book by entering either its title or the name of one of its authors. The search is case-insensitive, and all matched books' information is displayed.

- **Add a new book:** Add a new book to the library by providing required information such as serial number, title, authors, price, and the number of available copies. The entered information is validated, and the new book is added to "booksInfo.txt" with borrowed copies set to 0.

- **Remove a book:** Remove a book from the library by entering its serial number. The program displays book information and asks for confirmation before removal. A book can only be removed if it has no borrowed copies.

- **Borrow a book:** Borrow a book by entering its serial number and user ID. The corresponding records in "booksInfo.txt" and "borrowedInfo.txt" are updated to reflect the borrowing.

- **Return a book:** Return a borrowed book by entering its serial number and user ID. The corresponding records are updated to reflect the return.

## How to Use

1. Clone this repository to your local machine.
2. Navigate to the repository directory.
3. Run the Python script `library_management.py`.
4. Follow the on-screen instructions to interact with the Library Management System.

## Files

- `library_management.py`: The main Python script implementing the Library Management System.
- `booksInfo.txt`: Stores information about available books.
- `borrowedInfo.txt`: Stores information about borrowed books.
- `README.md`: This file, providing information about the project.

## Team Members

- [Your Name](https://github.com/yourusername)
- [Teammate 1's Name](https://github.com/teammate1username)
- [Teammate 2's Name](https://github.com/teammate2username)

## Project Report

Please refer to the separate Word file named "ProjectReport.docx" for the detailed project report, including the description of problem-solving approaches, contribution of each team member, description of functions, and screenshots of the running code.

## Presentation

We will be presenting our project during the scheduled presentation in the last week of the term. Each team member will demonstrate the functionalities of the program and be ready to answer questions about the code.

## Grading Policy

The project is graded based on various aspects, including the report, code quality, comments, modularity, and presentation. The total project weight is 100 points.

For more information, refer to the project guidelines provided in the course material.

## Submission

- The deadline for submitting the project is Tuesday, December 29, before midnight.
- Submission is through Blackboard, where a zipped file containing the Jupyter Notebook file and the Word file should be submitted.

## Note

The project is developed using the concepts covered in the course lectures and labs. The use of any additional, uncovered material or libraries is not allowed. Each team member should contribute equally to the project.

For any questions or clarifications, feel free to reach out to the team members or the course instructor.

---

**Appendix A: Sample Runs** (Refer to the provided document for sample runs)

