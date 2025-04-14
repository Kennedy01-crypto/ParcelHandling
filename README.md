# ParcelHandling

Final Year Project

## Project Description

ParcelHandling is a web-based application designed for tracking parcels efficiently. It allows users to enter tracking numbers and view the status of their parcels in real-time.

## Features

- **Parcel Tracking**: Users can enter a tracking number to retrieve the current status and history of their parcels.
- **User Management**: Admins can manage users, including adding, updating, and deleting user accounts.
- **Parcel Management**: Admins can create, update, and delete parcel records.
- **Reporting**: Generate reports based on parcel data within specified date ranges.

## Installation

1. Clone the repository to your local machine.
2. Ensure you have a web server (like WAMP) running.
3. Import the `cms_db.sql` file into your database to set up the necessary tables.
4. Update the `db_connect.php` file with your database credentials.

## Usage

1. Navigate to the application in your web browser.
2. Use the login page to access the admin dashboard.
3. From the dashboard, you can manage users and parcels, as well as track parcels using the tracking feature.

## File Descriptions

- **track.php**: The main file for tracking parcels. It includes an input field for the tracking number and displays the parcel history.
- **ajax.php**: Handles AJAX requests for various actions, including retrieving parcel history.
- **admin_class.php**: Contains the core functionality for user and parcel management, including methods for logging in, saving, updating, and deleting records.

## Contributing

Feel free to fork the repository and submit pull requests for any improvements or features you would like to add.

## License

This project is licensed under the MIT License.
