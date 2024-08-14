# BusBuddy
Final Capstone Project

BusBuddy - Mobile Ticketing Application

BusBuddy is a mobile ticketing application designed to streamline the process of booking and paying for bus tickets, specifically for the Ashesi University bus transit system. The application aims to enhance the convenience, security, and overall user experience for Ashesi University staff and faculty.

Features

Cross-Platform Support: BusBuddy is built using Flutter, providing support for both Android and iOS platforms.
Admin Panel: Managed through a PHP-based admin panel, allowing administrators to oversee bookings, update schedules, and generate reports.
Digital Ticketing: Eliminates the need for paper tickets, promoting eco-friendly practices.
Multiple Payment Options: Integrates with popular payment gateways such as Paystack, Stripe, Razorpay, and Flutterwave for secure transactions.
Real-Time Notifications: Keeps users informed with updates on bookings, payments, and bus schedules.
Prerequisites

To run and manage the BusBuddy application, the following tools and technologies are required:

Flutter SDK: Version 3.16.0 or higher
Dart SDK: Version 3.2.0 or higher
Android Studio: Version 4.1.2 or higher
MySQL Database: Version 5.6 or higher
PHP: Version 8.0 or higher for the admin panel
Apache HTTP Server: For hosting the admin panel

Setup Instructions

Flutter and Dart Setup
Install Flutter SDK:
Download and extract the Flutter SDK from the official website.
Update your system's PATH variable to include the Flutter bin directory.

Install Dart SDK:
Dart comes bundled with Flutter, so installing Flutter should automatically set up Dart.

Set Up Android Studio:
Install Android Studio and configure it for Flutter development by adding the Flutter and Dart plugins.

Database Configuration:
Create a MySQL database named BusBuddy and import the provided BusBuddy.sql file.


Run the Application:
After setting up the database and configuring the server, run the application to ensure everything is connected and functioning.

Building and Running the Application

Get Dependencies:
Run flutter pub get to install all the dependencies listed in the pubspec.yaml file.

Build and Run:
Open the project in Android Studio, select a target device, and click the run icon to build and deploy the application.
or
Run the following command in your terminal:
flutter run

Login details:
Number: +233 543477274
Password: 1234

Admin Panel Access:

Turn on the following servers:
MySQL Database
Apache Web Server

Admin Panel Setup
Create a Subdomain:
Set up a subdomain on your hosting server (e.g., subdomain.yourdomain.com).
Upload the admin panel files to the public_html/ directory of your server.

Move the busbuddyadmin directory to your htdocs folder

Access the admin panel by navigating to the subdomain you created (e.g., subdomain.localhost)

Log in to the admin panel using the default credentials provided.
Username: admin
Password: admin@123
