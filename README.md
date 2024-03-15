
# Library Management System
Welcome to the Library Management System project repository. This project is designed to help manage the operations of a library, including tracking information about books, employees, customers, and book issuances and returns.

# Description
The Library Database Management System is a comprehensive solution designed to streamline the operations of a library. It facilitates efficient management of books, patrons, transactions, and administrative tasks. This system provides librarians and administrators with tools to catalog books, manage memberships, track borrowing and returning activities, generate reports, and more.

# Features
This project consists of a database schema and SQL queries to perform various operations within a library environment. The database includes the following tables:
1. **Branch**: Information about library branches such as branch number, manager ID, address, and contact number.
2. **Employee**: Details of library staff including employee ID, name, position, salary, and the branch they are assigned to.
3. **Books**: Data related to books available in the library including ISBN, title, category, rental price, availability status, author, and publisher.
4. **Customer**: Information about library patrons including customer ID, name, address, and registration date.
5. **IssueStatus**: Records of books issued to customers including issue ID, customer ID, book name, and issue date.
6. **ReturnStatus**: Records of books returned by customers including return ID, customer ID, book name, and return date.

# ***Queries***
- Retrieve book title, category, and rental price of available books.
- ist employee names and salaries in descending order of salary.
- Retrieve book titles and corresponding customers who have issued those books.
- Display total count of books in each category.
- Retrieve employee names and positions for employees with salaries below Rs.50,000.
- List customer names who registered before 2022-01-01 and have not issued any books yet.
- Display branch numbers and total count of employees in each branch.
- Display names of customers who issued books in June 2023.
- Retrieve book titles containing "history".
- Retrieve branch numbers along with count of employees for branches having more than 5 
  employees.

# ***Additional Tasks Implemented***
- Explore the following queries to retrieve specific information from the database:

- Retrieve the list of available books along with their titles, authors, and categories.
- Display the details of patrons who have borrowed books, including their names, contact information, and borrowed book titles.
- Generate a report on the total number of books in each genre category.
- List the most borrowed books along with the corresponding patron details.
- Display the names and contact information of patrons who have overdue books.
- Retrieve information on popular authors based on the number of books borrowed.
- Generate a report on the average borrowing duration for each book category.
- List the patrons who have borrowed books written by a specific author.
- Display the total number of books borrowed by each patron.
- Generate a report on the total fines collected for overdue books.
- 
# Contribution
Contributions to the Library Database Management System project are encouraged and appreciated. Whether it's bug fixes, feature enhancements, or suggestions for improvements, feel free to open an issue or submit a pull request. Your contributions help make the system more robust and user-friendly for library administrators and patrons alike. Thank you for your support!

# Conclusion
In conclusion, this Library Management System project provides an efficient solution for organizing and managing library resources. Through the use of MySQL and SQL queries, the system effectively handles book management, employee tracking, customer records, and transaction management. With its user-friendly interface and comprehensive features, it streamlines library operations and enhances user experience. 
