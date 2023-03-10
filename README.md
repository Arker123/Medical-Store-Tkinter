# Medical-Store-Tkinter

A simple Medical Store Management System built in Python using Tkinter and MySQLdb is a desktop application that helps in managing the day-to-day activities of a medical store. It is designed to automate the process of maintaining inventory.

The application has a user-friendly interface that is built using Tkinter, a Python GUI toolkit. The database management system used is MySQLdb, which is a Python interface to MySQL.

Some of the key features of this Medical Store Management System include:

    Inventory Management: The application allows the user to manage the inventory by adding, updating, and deleting items. The user can also view the current stock level, and expiry date of the products.

    Sales Management: The system allows the user to manage sales by creating new sales orders, updating existing orders, and deleting orders.

    User Management: The system allows the user to manage different user accounts with different levels of access.

The application works by connecting to the MySQL database, which stores all the data related to inventory, sales, and users. The application provides a graphical user interface for the user to interact with the database and perform various actions.

Overall, the Medical Store Management System built in Python using Tkinter and MySQLdb is a simple yet effective solution for managing the day-to-day activities of a medical store. It helps in streamlining the inventory management and sales processes, which leads to better productivity and efficiency.

To run (in Ubuntu):-

1. Install tkinker:-<br>
  `pip install tk`
2. Install MySQLdb<br>
  `pip install mysqlclient`
3. Edit Line 11 of med.py with Username and Password<br>
  `mydb = MySQLdb.connect("localhost", "username", "password") #Edit Here`
  

  
