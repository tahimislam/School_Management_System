# School Management System Database Project

This repository contains a school management system database project implemented using Oracle SQL Plus 21c. The project aims to provide a structured database schema for managing teachers, students, classes, subjects, results, and related information in a school environment.

## Table of Contents

- [Introduction](#introduction)
- [Database Schema](#database-schema)
- [Technologies Used](#technologies-used)
- [Setup and Usage](#setup-and-usage)
- [Contributing](#contributing)

## Introduction

The School Management System Database Project is designed to facilitate efficient data management for schools, allowing administrators to manage teachers, students, classes, subjects, results, and more. The project uses an Oracle SQL Plus 21c database to store and retrieve data related to the school's operations.

## Database Schema

The project's database schema is structured as follows:

- `TEACHER`: Stores information about teachers, including their ID, gender, name, date of birth, blood group, address, and phone number.

- `CLASS`: Represents classes offered by the school, including class ID and total number of students.

- `STUDENT`: Contains details about students, such as student ID, associated class, gender, name, date of birth, blood group, address, and phone number.

- `APPOINTED_TEACHER`: Establishes a relationship between classes and teachers, indicating which teacher is appointed to a specific class.

- `CLASS_ROOM`: Stores information about class rooms, including room number, associated class, and capacity.

- `SUBJECT`: Represents subjects taught in the school, including subject code, name, and associated class.

- `RESULT`: Holds student-specific results, including student ID, subject code, marks, GPA, and grade.

### Schema

![Schema](https://github.com/tahimislam/School_Management_System/assets/66324297/51943087-40b4-4411-af6e-2cef394b05a2)

## Technologies Used

- Oracle SQL Plus 21c: The primary database management system used for this project.
- Markdown: Used for writing documentation and this README file.

## Setup and Usage

1. **Database Setup**: Ensure you have Oracle SQL Plus 21c installed and set up. You can download it from [Oracle's official website](https://www.oracle.com/database/technologies/).

2. **Clone the Repository**: Clone this repository to your local machine using the following command:

- `git clone https://github.com/tahimislam/School_Management_System.git`

3. **Database Creation**: Use the provided SQL scripts to create the database schema and populate it with sample data. Run the scripts in the following order:

- `create_tables.sql`: Creates the necessary tables.
- `insert_sample_data.sql`: Inserts sample data for testing.

4. **Queries and Operations**: Utilize Oracle SQL Plus to perform queries and operations on the database. You can execute SQL queries using the SQL Plus command-line interface.

## Contributing

Contributions to this project are welcome! If you find any issues or want to add new features, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/new-feature`.
3. Commit your changes: `git commit -m 'Add a new feature'`.
4. Push the branch: `git push origin feature/new-feature`.
5. Open a pull request.


---

Feel free to explore the repository and adapt the database schema to your specific school management needs. If you encounter any issues or have suggestions, please don't hesitate to reach out!

