# Library Management System

## Overview
Welcome to the DEPI Graduation Project

The **Library Management System** is a web application built with **ASP.NET Core** that helps libraries manage their inventory, track book checkouts, handle book returns, and calculate penalties for late returns. The system provides user authentication for librarians and members and includes a book search functionality.

## Features

- **Book Inventory Management**: Add, update, and delete books in the system.
- **Member Registration**: Register and manage library members.
- **Book Checkouts and Returns**: Track which books are checked out and returned, along with due dates.
- **Late Penalty Calculation**: Automatically calculate penalties for overdue books.
- **User Authentication**: Secure login and role-based access for librarians and members.
- **Search Functionality**: Search for books by title, author, or genre.

## Technologies Used

- **Backend**: ASP.NET Core (C#)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQL Server
- **ORM**: Entity Framework Core
- **Authentication**: ASP.NET Core Identity
- **Version Control**: Git and GitHub

## Project Structure

- **Controllers**: Contains the logic for managing books, members, and user authentication.
- **Models**: Represents the data structures for books, members, and transactions.
- **Views**: The user interface components that handle displaying data to the user.
- **Database**: SQL Server database for storing books, members, and transaction data.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Abanoub-Emad/Library-Management-System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Library-Management-System
   ```
3. Install the required NuGet packages:
   ```bash
   dotnet restore
   ```
4. Update the database:
   ```bash
   dotnet ef database update
   ```
5. Run the application:
   ```bash
   dotnet run
   ```

## Usage

- **Librarians** can log in to manage books, view overdue books, and manage members.
- **Members** can log in to browse the available books, check their borrowed books, and return them.

## DEMO 
### Registration
![image](https://github.com/user-attachments/assets/fbb00b17-e484-49c9-8ccc-e1574daad65b)
![image](https://github.com/user-attachments/assets/18ba1387-c688-4f59-b8ec-cd2e8d5d9fc3)


### Libirian can add | delete | Edit books details
![image](https://github.com/user-attachments/assets/20c28930-896e-4ffe-bad1-abbe7e7079a7)


### Member View: Can search for books and borrow them.
![image](https://github.com/user-attachments/assets/0ade1a06-2400-4ec1-9cc7-03386c74bec8)

## Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request.
