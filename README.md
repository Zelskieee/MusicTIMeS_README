# ![MusicTIMeS Logo](path/to/logo.png)

# README.txt for MusicTIMeS

## Project Title:
Musical Traditional Instrument Maker Enterprises e-Commerce System (MusicTIMeS)

## Project Description:
MusicTIMeS is a web-based e-commerce system designed to digitize and streamline the order management process for traditional musical instrument makers in Malaysia. The system provides an online platform for enterprises to manage their products, orders, payments, and customer interactions efficiently. It aims to enhance the operational efficiency of these enterprises, attract more customers, and support the preservation and global reach of traditional musical instruments.

## Modules:
1. **Register**:
   - Customers and enterprise owners can create accounts.
   - Secure password management and OTP-based email verification.

2. **Login**:
   - Customers and enterprise owners can log into the system.
   - Customers can reset forgotten passwords.

3. **Manage Profile**:
   - Customers and enterprise owners can update their personal information and change passwords when logged in.

4. **Manage Product**:
   - Enterprises can add, edit, and delete categories and products.

5. **Manage Order**:
   - Customers can view products, add items to the cart, place orders, cancel orders, track orders, and download invoices in PDF format.
   - Enterprises can view customer orders and provide tracking numbers to ship orders to customers.

6. **Manage Payment**:
   - Integration with Stripe for secure online payments.
   - Customers can make online payments using credit or debit cards and online banking.
   - Enterprises can view and manage payment transactions.

7. **Manage Feedback**:
   - Customers can provide ratings and feedback for purchased products.
   - Enterprises can view customer feedback.

8. **Generate Report**:
   - Enterprises can generate and download sales reports in CSV format.
   - Sales reports include summaries, bar charts, and lists of top-selling products.

## Development Tools:
- **Visual Studio Code**: For code editing and development.
- **XAMPP**: For local server environment.
- **phpMyAdmin**: For database management.
- **Composer**: For dependency management.
- **GitHub**: For version control and project management.
- **Stripe**: For payment processing.

## Installation and Setup:
1. **Prerequisites**:
   - XAMPP or any other local server environment.
   - PHP 7.4 or higher.
   - MySQL 5.7 or higher.
   - Composer (for dependency management).

2. **Installation Steps**:
   - Clone the repository: `git clone https://github.com/Zelskieee/musictimes.git`
   - Navigate to the project directory: `cd musictimes`
   - Install dependencies using Composer: `composer install`
   - Set up the database:
     - Import the provided SQL file (`database/musictimes.sql`) into your MySQL database.
     - Configure the database connection in `db.php`.
   - Start the local server using XAMPP or an equivalent tool.
   - Access the application in your web browser at `http://localhost/musictimes`.

3. **Web Hosting URL for MusicTIMeS**:
   - [MusicTIMeS Web Hosting](https://musictimessystem.000webhostapp.com)

## System Architecture:
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Payment Gateway**: Stripe

### System Design Overview:
- **Customer Modules**: Register, Login, Manage Profile, Manage Order, Manage Payment, Manage Feedback.
- **Enterprise Modules**: Register, Login, Manage Profile, Manage Product, Manage Order, Manage Payment, Manage Feedback, Generate Report.
- **Database Schema**: 
  - Tables include Customer, Enterprise, Product, Order, Order_item, Payment, Cart, Feedback, Category.

## Usage Instructions:
1. **Register and Login**:
   - Access the registration page to create a new account.
   - Verify your email using the OTP sent to your registered email address.
   - Log into the system using your registered email and password.

2. **Manage Profile**:
   - Navigate to the profile section to update your personal details or change your password.

3. **Manage Product (For Enterprises)**:
   - Access the product management section to add new products or update existing ones.
   - Provide detailed descriptions and images for each product.

4. **Placing Orders (For Customers)**:
   - Browse the product catalog and add desired items to the cart.
   - Track your orders from the order management section.
   - Download invoices.

5. **Managing Orders (For Enterprises)**:
   - View customer orders.
   - Provide tracking information for shipped orders.

6. **Make Payment (For Customers)**:
   - Proceed to checkout and select your preferred payment method.

7. **Providing Feedback (For Customers)**:
   - Rate and provide feedback for products after order completion.

8. **Generating Reports (For Enterprises)**:
   - Access the report generation section to view and download sales reports.

## Troubleshooting Tips:
- **Database Connection Issues**: Ensure your database credentials are correctly configured in `db.php`.
- **Dependency Issues**: Run `composer install` to ensure all dependencies are properly installed.
- **Server Issues**: Verify that XAMPP or your local server environment is running correctly.
- **Payment Processing Issues**: Check the Stripe payment link and configuration in the payment module.

## System Requirements:
- Operating System: Windows, macOS, or Linux
- Web Browser: Latest versions of Chrome, Firefox, Safari, or Edge
- Local Server: XAMPP, WAMP, or MAMP

## Contributors:
- Mohamad Arif Azinuddin Bin Zaidi
- Mohd Zainuri Bin Saringat (Supervisor)

## Contact Information:
![Arif Azinuddin](path/to/arif%20pakai%20blazer.png)
For any inquiries or support, please contact Mohamad Arif Azinuddin Bin Zaidi at chojjaarif2002@gmail.com.

## License:
This project is licensed under the Faculty of Computer Science and Information Technology, Universiti Tun Hussein Onn Malaysia under the Final Year Project II Course (BIC31704).

---

Thank you for using MusicTIMeS. We hope this system enhances your traditional musical instrument business by providing a modern and efficient way to manage your products and orders.
