# HTML Authentication POC

A simple Authentication Flow Proof of Concept built using pure HTML.
This project demonstrates navigation and redirection between multiple pages using anchor (`<a>`) tags without using CSS or JavaScript.

# Project Objective

To design a basic authentication workflow that includes:

1. Login Page
2. Registration Page
3. Forgot Password Page
4. Reset Password Page
5. Dashboard Page

All pages are interconnected using proper HTML redirections.

# Pages Included

1. login.html - User login form
2. register.html - New user registration form
3. forgot-password.html - Request password reset
4. reset-password.html - Update password form
5. dashboard.html - Welcome page after login

# Navigation Flow

- Login -> Dashboard
- Login -> Forgot Password
- Login -> Reset Password
- Login -> Register
- Register -> Login
- Forgot Password -> Reset Link -> Login
- Reset Password -> Login
- Dashboard -> Logout -> Login

All redirections are implemented using anchor (`<a>`) tags only.

# Technologies Used
 
 HTML5

# How to Run the Project (Using XAMPP)

1. Download or clone this repository 

2. Move the project folder to:

   C:\xampp\htdocs\

3. Start Apache from XAMPP Control Panel

4. Open the below link in browser:

   http://localhost/html-authentication-poc/login.html


# Author

Sushmitha V
