Car Rental Management System
A web-based application developed to automate car rental operations, replacing manual record-keeping with a centralized relational database. The project focuses on data integrity, normalization, and role-based access control.

Technical Stack
Backend: PHP for server-side logic and session management.

Database: MySQL relational database.

Environment: Developed and tested using the XAMPP local server environment.

Frontend: Built with HTML5 and CSS3.

Core Functionality
Administrative Control: A secure dashboard for managing the vehicle fleet, registering customers, and monitoring active rentals.

Inventory Tracking: Real-time monitoring of car availability, where the system updates a vehicle's status to 'Rented' upon booking.

Automated Rent Calculation: A backend engine that calculates total costs based on the vehicle's daily rate and duration of the rental.

Business Intelligence: A reporting module providing a high-level overview of total revenue and live inventory statistics.

Installation and Setup
Clone the repository to your local machine.

Open XAMPP and start the Apache and MySQL services.

Import the provided SQL database file through phpMyAdmin.

Configure the database connection settings in the config.php file.

Place the project folder in the htdocs directory and access it via your web browser at http://localhost/project_folder/.

Future Scope
Integration of online payment gateways such as Stripe or PayPal.

Development of automated SMS and Email notification systems for rental reminders.

GPS integration for real-time vehicle tracking and security.
