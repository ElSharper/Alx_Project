# E-commerce Website

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Credits](#credits)
- [License](#license)

## Project Overview

This project is an e-commerce website developed as a final project for the ALX Software Engineer program. The website allows users to browse products, add them to their cart, and make purchases. The project demonstrates proficiency in both front-end and back-end development, utilizing various web technologies.

## Features
- User authentication (registration, login, logout)
- Browse products by category
- Product search functionality
- Add products to shopping cart
- Checkout process
- Order management for users (view order history)
- Admin panel for managing products and orders
- CRUD (Create, Read, Update, Delete) operations for products

## Technologies Used

### Front-end:
- HTML
- CSS (Bootstrap)
- JavaScript

### Back-end:
- PHP (native)
- MySQL

## Setup Instructions

### Prerequisites:
- WAMP Server (Windows, Apache, MySQL, PHP)
- Local phpMyAdmin (included with WAMP)

### Steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Alx_Project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Alx_Project
    ```
3. Set up the database:
    - Open WAMP Server and ensure that Apache and MySQL services are running.
    - Open phpMyAdmin by navigating to [http://localhost/phpmyadmin](http://localhost/phpmyadmin) in your web browser.
    - Create a new database named `Alx_Project`.
    - Import the SQL file located in the `database` folder:
        - In phpMyAdmin, select the `Alx_Project` database.
        - Go to the "Import" tab.
        - Click "Choose File" and select `Alx_Project.sql`.
        - Click "Go" to import the database schema and data.

4. Configure the database connection:
    Edit the `config.php` file in the root directory to match your database credentials:
    ```php
    <?php
    $db_name = 'mysql:host=localhost;dbname=Alx_Project';
    $user_name = 'root';
    $user_password = '';

    ?>
    ```

5. Run the application:
    - Ensure WAMP Server is running.
    - Place the project directory inside the `www` directory of your WAMP installation (usually located at `C:\wamp64\www\`).
    - Access the website by navigating to [http://localhost/Alx_Project](http://localhost/Alx_Project) in your web browser.

## Usage

### Registration and Login:
- Users need to register with a valid email address and password.
- Registered users can log in to access their account, view products, and make purchases.

### Browsing Products:
- Products are displayed on the home page and can be browsed by categories.
- Use the search bar to find specific products.

### Shopping Cart:
- Add products to the shopping cart.
- View and manage the items in the cart.

### Checkout:
- Proceed to checkout to complete the purchase.
- Orders will be processed and stored in the database.

### Admin Panel:
- Admin users can log in to the admin panel.
- Manage products and orders through the CRUD interface.
- Admin Login
  UserName : admin
  Password : admin

## Screenshots

(Add screenshots of your project here)

## Credits
- Bootstrap: For providing the front-end framework.
- ALX Software Engineer Program: For guidance and support throughout the project.
- Any other libraries or resources used.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
