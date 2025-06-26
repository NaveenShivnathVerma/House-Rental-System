🏠 House Rental System
A simple, web‑based system for managing rental property listings — complete with user authentication and contact forms, built using PHP, MySQL, and Bootstrap.

📌 About the Project
This House Rental System allows property owners to post, manage, and display rental listings, and lets users browse and contact owners securely. It's a useful tool to learn full-stack web development with PHP and MySQL.

🛠️ Built With
PHP ≥ 7.4
MySQL / MariaDB
Bootstrap (HTML/CSS)
XAMPP (for Apache + PHP + MySQL)
✅ Prerequisites
Before you begin, ensure you have:

XAMPP installed (includes Apache, PHP, MySQL)
PHP 7.4 or higher
MySQL or MariaDB (via XAMPP)
🚀 Installation
Clone the repository
git clone https://github.com/NaveenShivnathVerma/House-Rental-System.git
Move to XAMPP’s htdocs directory

Import the database

Open phpMyAdmin → choose your database → “Import” → select database.sql if provided

Or manually create tables if not

Configure database connection

Open config.php, or locate mysqli_connect(...)

Set host, username, password, and database_name

Run the application

Start Apache & MySQL in XAMPP

🧑‍💻 Usage Register or login as an owner or user

Owners can add/edit/delete listings

Users can browse listings and contact owners via form

Update contact_me.php to handle email notifications

🧪 Testing Browse through pages (Home, Listings, Contact)

Submit form entries and check email notifications

Add a sample rental and confirm it appears

🤝 Contributing Fork this repo

Create a feature branch:

bash Copy Edit git checkout -b feature-name Commit your work:

bash Copy Edit git add . git commit -m "Add awesome feature" git push origin feature-name Open a Pull Request for review

🧭 Roadmap Add user roles and admin dashboard

Upgrade UI to Bootstrap 5

Enable image uploads for listings

📬 Contact Naveen Shivnath Verma GitHub Profile — feel free to reach out!