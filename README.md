# Email Generation System

This is a simple Java console-based project that generates official email addresses for new employees in a company. The system takes the employee's name and department as input, generates a strong random password, and creates a unique email ID even if multiple employees have the same name.

The project is built using core Java and demonstrates the use of object-oriented programming principles.


# Features

- Creates unique email addresses using name, department, and a unique number
- Generates random secure passwords for each user
- Assigns departments through user input
- Allows:
  - Setting an alternate email
  - Changing the password
  - Adjusting mailbox capacity
  - Viewing employee details like name, email, and mailbox size


# Concepts Covered

This project covers the following OOP concepts:

- Encapsulation: Variables are private and accessed through setters and getters
- Inheritance: The Email class extends a base User class
- Polymorphism: The showInfo() method is overridden in the Email class
- Abstraction: The logic for department selection and password creation is hidden inside methods




