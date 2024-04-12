
# Welcome to PHP Project

This repository contains a dynamic PHP project. The following instructions will help you through the process of setting up and running this project on your local system using XAMPP.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Database Setup](#database-setup)
- [Running the Project](#running-the-project)


## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest version of XAMPP.
- You have downloaded the zip file of this project.

## Installation

To install the project, follow these steps:

1. Extract the downloaded zip file into the `C:/xampp/htdocs/` directory.
2. Open the XAMPP control panel and start the Apache and MySQL services.

If the MySQL service does not start and shows that the port is already in use, follow these steps:

- Open the command prompt as an administrator.
- Run the command: `netstat -a -n -o | find "3306"`.
- Note the PID of the process using port 3306.
- Run the command: `taskkill /PID {PID} /F`, replacing `{PID}` with the actual PID noted in the previous step.
- Try starting the MySQL service again.

## Database Setup

To set up the database:

- Click on the MySQL Admin button in XAMPP to open phpMyAdmin.
- Create a new database named 'trip'.
- In this database, create a table named 'passengers' with the appropriate table structure.
  ![Screenshot 2024-04-13 004201](https://github.com/Nauti-Rohit/majorProject-PHP-/assets/85772545/6545bd34-e8d5-4aca-9908-dde2df82981f)



## Running the Project

To run the project:

- Open a web browser and navigate to 'http://localhost/majorProject(PHP)/'.
- Fill out the form details and submit it.

If everything is set up correctly, the information submitted through the form should be reflected in the MySQL database.

That's all from my side, thank you.

Happy coding! 😊
