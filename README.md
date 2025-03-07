

### Store POS – A Lightweight Yet Powerful JavaFX-Based Point of Sale System

Store POS is an intuitive and efficient Point of Sale (POS) solution designed for both retail and wholesale businesses. Developed in JavaFX, it offers essential functionalities such as purchasing, sales, and inventory management, with plans to introduce a finance module in future updates.  

This project aims to simplify store operations, enabling businesses to streamline transactions, track stock levels, and generate detailed reports. We also welcome open-source contributors to help expand this system into a comprehensive ERP solution with accounting and finance features built in Java.  

---

## Key Functionalities  
✔ Purchase Management – Easily manage supplier transactions and track purchases.  
✔ Sales Processing – Conduct retail and wholesale sales seamlessly.  
✔ Inventory Control – Monitor stock, update product details, and prevent shortages.  
✔ Report Generation – Create detailed reports using **JasperReports**.  
✔ Database Integration – Seamlessly connects with an **Oracle Database** for data handling.  
✔ User-Friendly UI – Developed with **JavaFX** for a modern and interactive interface.  



### Technology Stack  

| Component                |      Version |
|--------------------------|-------------|
| Programming Language     | Java (1.8.0_66) |
| UI Framework            | JavaFX |
| Reporting Tool          | JasperReports (6.16.0) |
| Third-Party Libraries   | ControlsFX (8.40.14) |
| Database                | Oracle Database (11.2.0.1.0) |
| IDE                     | NetBeans IDE (8.0.2) |
| UI Design Tool          | JavaFX Scene Builder (11.0.0) |
| Database Management     | TOAD for Oracle (10), SQL Developer |

---

### Installation & Setup Guide  

Follow these steps to install and run the **Store POS system**:  

#### 1️⃣ Clone the Repository 
Download or clone the project from the repository.  

#### **2️⃣ Configure the Database**  
- Open `DbConnection.java` inside `src/database/DbConnection`.  
- Update the **database credentials** to match your Oracle Database configuration.  

#### **3️⃣ Import the Database Schema**  
- Use **SQL Developer, TOAD, or SQL++** to import `STOREPOS.DMP`.  
- Ensure the schema is properly set up.  

#### **4️⃣ Run the Application**  
- Open the project in **NetBeans IDE**.  
- Compile and run the application using the **JavaFX runtime**.  
- Alternatively, run it via the command line.  

---

### Screenshots & Modules  

📍 **Dashboard** – View an overview of store operations.  
📍 **Sales Module** – Process transactions quickly and efficiently.  
📍 **Purchase Module** – Track and manage supplier orders.  
📍 **Inventory Management** – Keep stock levels updated in real-time.  
📍 **Reports** – Generate invoices, sales reports, and inventory summaries.  

---

