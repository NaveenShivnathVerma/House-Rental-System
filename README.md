# House Rental System

A simple web-based system to list, search, and manage rental properties with user authentication and contact forms.

## 🔎 Overview
- Built with PHP, MySQL, HTML/CSS (Bootstrap).
- Enables property owners to post listings.
- Allows users to browse and contact owners.

## ⚙️ Getting Started

### Prerequisites
- PHP ≥ 7.4
- MySQL / MariaDB
- XAMPP installed (Apache, PHP, MySQL)

### Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/NaveenShivnathVerma/House-Rental-System.git
Copy to XAMPP htdocs:

bash
Copy
Edit
xcopy "House-Rental-System" "C:\xampp\htdocs\House-Rental-System" /E /I
MySQL database:

Import database.sql (agar available ho) via phpMyAdmin.

Otherwise manually create database & tables.

Configure database connection in PHP:
Edit config.php agar hai, ya mysqli_connect() keywords ke andar host, username, password, database name fill karein.

Start Apache & MySQL through XAMPP, then open:

arduino
Copy
Edit
http://localhost/House-Rental-System/
🖥️ Usage
Register/login for owner or user.

Owners: add/edit/delete property listings.

Users: browse & contact property owners.

Modify contact_me.php to receive email notifications.

🧪 Testing
Visit various pages to ensure they load.

Test form submissions.

Add sample property and verify it shows.

📸 Screenshots
(Optional: add screenshots in assets/images/ then include: )

md
Copy
Edit
![Home Page](assets/images/home.png)
🤝 Contributing
Fork the repo.

Create a feature branch: git checkout -b feature-name

Commit and push: git push origin feature-name

Make a pull request.

🧭 Roadmap
Add user roles (admin panel).

Improve UI/UX (Bootstrap v5).

Add image upload for properties.

📄 License
This project is under the MIT License. See LICENSE for details.

📬 Contact
Naveen Shivnath Verma – GitHub – feel free to reach out!
