# Complaint Management System

## Description
The Complaint Management System is a web application designed to streamline the process of lodging, tracking, and managing complaints within an organization. This system enables users to register and submit complaints, which can then be reviewed and addressed by relevant personnel. Built using PHP, CSS, JavaScript, and a MySQL database, it provides an organized and efficient way to resolve user issues.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)

## Installation
Follow these steps to set up and run the project locally:

1. **Download and Install XAMPP:**
   - Download XAMPP from [Apache Friends](https://www.apachefriends.org/index.html) and install it on your machine.

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/surendraguna/Complaint-Management-System.git

3. **Move the Project to XAMPP:**
   - Copy or move the cloned repository into the `htdocs` directory of your XAMPP installation (typically found in `C:\xampp\htdocs` on Windows).

4. **Set Up the Database:**
   - Import the SQL database file (found in the ```database``` folder) into your MySQL server using phpMyAdmin.

5. **Configure Database Connection:**
   - Open `db_connection.php` and update the database credentials (host, username, password, database name) as per your local setup.
6. **Start XAMPP:**
   - Launch the XAMPP Control Panel and start the Apache and MySQL modules. Ensure that both services are running without errors.

7. **Access the Application:**
   - Open your web browser and go to `http://localhost/Complaint-Management-System` to use the application. You should see the home page of the Complaint Management System.

## Usage

- **Register and Sign In:**
  - New users can register via `signup.php`. After registering, users can sign in with their credentials on `signin.php`.

- **Submit a Complaint:**
  - After signing in, users can navigate to `add_complaint.php` to submit a new complaint. Fill out the required fields and click the submit button to register your complaint.

- **Track Complaint History:**
  - Users can view the status of their complaints by navigating to `history.php`. This page displays a list of all submitted complaints along with their current status.

- **Admin Access:**
  - Admin users have additional privileges such as viewing all complaints (`list_of_complaints.php`), managing users (`remove_user.php`), and adding new users (`add_member.php`).

## Features
  - **User Authentication**: Register, sign in, and manage accounts.
  - **Complaint Submission**: Users can add and submit complaints.
  - **Complaint History**: Users can view the status and history of their complaints.
  - **Admin Control Panel**: Admins can manage complaints and users.
  - **Profile Management**: Users can update profile details, change passwords, and upload profile pictures.

## Contributing
Contributions are welcome! Follow these steps if you wish to contribute:
1. Fork the repository.
2. Create a new branch (git checkout -b feature-name).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-name).
5. Open a pull request for review.
