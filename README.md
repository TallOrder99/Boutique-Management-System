# Boutique-Management-System

A .NET Core and SQL-based web application for managing boutique inventory, sales, and customer data.

📌 Features

✔ Inventory Management – Track products, categories, and stock levels.

✔ Sales & Order Processing – Record purchases, returns, and customer history.

✔ Automated Stock Alerts – Scheduled job checks for low stock and sends notifications.

✔ Customer Management – Store client details and purchase history.

✔ RESTful API – Built with ASP.NET Core for seamless frontend/backend communication.

✔ SQL Database – Uses SQL Server / PostgreSQL / MySQL for data persistence.

🛠 Technologies Used

Backend: .NET Core 6+ (C#)

Database: MySQL

Frontend: React (optional)

🚀 Getting Started

Prerequisites

.NET 6+ SDK

 ySQL

Visual Studio 2022 / VS Code

Setup & Run
Clone the repository:

git clone https://github.com/your-repo/boutique-management-system.git
cd boutique-management-system


Configure the database:

Update appsettings.json:


"ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Database=BoutiqueDb;User Id=sa;Password=yourpassword;"
}


Apply database migrations:

dotnet ef database update


Run the application:

dotnet run
The app will start at: http://localhost:5000
