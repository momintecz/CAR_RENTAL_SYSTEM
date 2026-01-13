Car Rental Management System
A web-based application developed to automate the manual processes of car rentals, inventory management, and customer record-keeping. This project was developed as part of the Database Systems (AI2313) course.

 Features
Role-Based Authentication: Separate dashboards for Admin and Customers using PHP Sessions.

Vehicle Management: Admin can add, update, and remove vehicles from the fleet.

Dynamic Rent Calculation: Automatically calculates total rent based on the number of days and car category.

Live Reporting: Real-time tracking of available cars, cars currently on rent, and total revenue.

Database Integrity: Uses MySQL relational database with normalized tables to prevent data redundancy.

 Tech Stack
Frontend: HTML5, CSS3, JavaScript

Backend: PHP

Database: MySQL (Relational)

Server: XAMPP (Local Hosting)

 System Requirements
XAMPP Control Panel (Apache & MySQL)

Web Browser (Chrome, Firefox, or Edge)

PHP 7.4+

🔧 Installation & Setup
Clone the Repository:

Bash

git clone https://github.com/your-username/car-rental-system.git
Database Setup:

Open XAMPP and start Apache and MySQL.

Go to http://localhost/phpmyadmin/.

Create a new database (e.g., car_rental_db).

Import the .sql file provided in the /database folder.

Configuration:

Open config.php and update your database credentials (hostname, username, password, and database name).

Run the Project:

Move the project folder to C:/xampp/htdocs/.

Access the system at http://localhost/car_rental_system/.

Database Schema (ERD)
The system is designed with a focus on Normalization to ensure data integrity. The primary entities include:

Users: Stores credentials and roles (Admin/User).

Vehicles: Stores car details and availability status.

Customers: Stores personal information (CNIC, Phone, etc.).

Rentals: The core transactional table connecting customers and vehicles.

 Future Scope
Integration with Online Payment Gateways (Stripe/PayPal).

Automated SMS/Email notifications for rental reminders.

GPS tracking for real-time vehicle monitoring.
