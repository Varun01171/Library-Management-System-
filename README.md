📚 Library Management System

A Library Management System (LMS) built with PHP and MySQL to manage books, users, and transactions like issuing and returning books.
It provides an Admin Section where all operations of the library can be managed efficiently.

🚀 Features
👤 User Management
Add, update, and delete users (students/staff).
Assign unique IDs for tracking.
📖 Book Management
Add, update, and delete books.
Search books by title, author, or category.
Track available vs. issued books.
🔄 Transaction Management
Issue and return books.
Maintain due dates and borrowing history.
🛡️ Admin Section
Secure login for Admin.
Manage all books and users from one dashboard.
Approve/reject issue requests.
Generate reports of issued/returned books.
📊 Reports
View total, issued, and available books.
Monitor usage statistics.
🛠️ Tech Stack
Frontend: HTML, CSS, Bootstrap (optional)
Backend: PHP (Core / OOP)
Database: MySQL
Server: Apache (XAMPP / WAMP / LAMP)

📂 Project Structure
Library-Management-System/
│── config/             # Database connection
│── admin/              # Admin dashboard & controls
│── user/               # User-side functionalities
│── assets/             # CSS, JS, images
│── index.php           # Login page
│── database.sql        # MySQL schema
│── README.md           # Documentation

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Varun01171/Library-Management-System-/tree/main
cd Library-Management-System

2️⃣ Setup Database
Open phpMyAdmin.
Create a new database (e.g., library_db).
Import database.sql into your database.
3️⃣ Configure Database Connection
Update config/db.php:
$servername = "localhost";
$username   = "root";
$password   = "";
$dbname     = "library_db";

4️⃣ Run the Project
Copy the project folder into htdocs (if using XAMPP).
Start Apache and MySQL from XAMPP.

Visit:
http://localhost/Library-Management-System
🔑 Admin Login
Default Username: admin
Default Password: admin123
Admin can add/manage books, users, and transactions from the dashboard.
🧪 Testing
Login as Admin.
Add users and books.
Try issuing and returning books.
Check reports in the Admin dashboard.
📌 Future Enhancements
Role-based access (Admin, Librarian, Student).
Fine calculation for late returns.
Barcode/QR integration for fast issue/return.
Email notifications for due dates.
