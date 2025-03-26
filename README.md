# **Boutique Management System**  

A **.NET Core** and **SQL**-based web application for managing boutique inventory, sales, and customer data.  

---

## **📌 Features**  
✔ **Inventory Management** – Track products, categories, and stock levels.  
✔ **Sales & Order Processing** – Record purchases, returns, and customer history.  s.  
✔ **Customer Management** – Store client details and purchase history.  
✔ **SQL Database** – Uses **SQL Server / PostgreSQL / MySQL** for data persistence.  

---

## **🛠 Technologies Used**  
- **Backend**: .NET Core 6+ (C#)  
- **Database**: MySQL  
- **Frontend**: Razor Pages 

---

## **🚀 Getting Started**  

### **Prerequisites**  
- .NET 6+ SDK  
- SQL Server / PostgreSQL / MySQL  
- Visual Studio 2022 / VS Code  

### **Setup & Run**  
1. **Clone the repository**:  
   ```sh
   git clone https://github.com/your-repo/boutique-management-system.git
   cd boutique-management-system
   ```  

2. **Configure the database**:  
   - Update `appsettings.json`:  
     ```json
     "ConnectionStrings": {
         "DefaultConnection": "Server=localhost;Database=BoutiqueDb;User Id=sa;Password=yourpassword;"
     }
     ```  

3. **Apply database migrations**:  
   ```sh
   dotnet ef database update
   ```  

4. **Run the application**:  
   ```sh
   dotnet run
   ```  
   - The app will start at: `http://localhost:5000`  

