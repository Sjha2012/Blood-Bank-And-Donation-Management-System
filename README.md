# Blood-Bank-And-Donation-Management-System
The **Blood Bank & Donation Management System** is a PHP-based web application designed to streamline blood donation processes. It includes separate layouts for administrators and users, enabling efficient management of blood donations, donors, and requests.

## Features

- **Admin Panel**:
  - Manage blood donation records.
  - View and update donor information.
  - Respond to blood requests.
- **User Panel**:
  - Register as a donor.
  - Search for blood groups.
  - Submit blood donation requests.
- **Additional Functionalities**:
  - Informative pages like "Why Donate Blood?" and "About Us."
  - Contact form for inquiries.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## Installation

1. Install [XAMPP](https://www.apachefriends.org/index.html) or [WAMP](https://www.wampserver.com/).
2. Start the Apache and MySQL modules in the XAMPP/WAMP control panel.
3. Clone the repository:
   ```bash
   git clone https://github.com/varunsardana004/Blood-Bank-And-Donation-Management-System.git
   ```
4. Place the project folder in the `htdocs` directory of your XAMPP/WAMP installation.
5. Import the database:
   - Open [phpMyAdmin](http://localhost/phpmyadmin/).
   - Create a new database (e.g., `blood_bank`).
   - Import the SQL file located in the `sql` folder of the project.
6. Configure the database connection:
   - Open `conn.php` in a text editor.
   - Update the database credentials (host, username, password, database name) to match your setup.

## Usage

1. Open your web browser and navigate to `http://localhost/Blood-Bank-And-Donation-Management-System`.
2. Use the application as a donor or admin:
   - **Donor**: Register, donate blood, and search for blood groups.
   - **Admin**: Log in to manage records and requests.

## Screenshots

(Add screenshots or GIFs here to showcase the interface.)

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributors

- [Sweety Kumari](https://github.com/Sjha2012)

---

Feel free to fork this repository and contribute to its development!
