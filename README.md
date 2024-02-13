# Health Insurance Management System
A dashboard website for a Health Insurance Company.
Built using **PHP**, **MySQL**, **HTML**, **CSS**

Login, logout, session, multilevel access, image uploads
are implemented here.

## Features
- Agents can create clients
- Agents can only edit and delete info of the client they created
- Master Agent can create, update, delete all clients and agents info
- Payment records and nominees can be added and managed by agents

## Deploy on localhost
Assuming **XAMPP** is already installed in your local machine

1. Clone into your **xampp/htdocs** folder
2. Edit the **hims/connection.php** file with your database username and password
2. Go to http://localhost/phpmyadmin
3. Create a database named **hims_final**
3. import the **hims_final.sql** file provided in **database backup** folder
4. Go to http://localhost/hims/ if you see a login page, it is working
