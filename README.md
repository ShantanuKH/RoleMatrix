# RoleMatrix - RBAC Project 🛡️🔐

## Overview 📚
This project is a full-stack implementation of Role-Based Access Control (RBAC) using Express.js, Passport.js, EJS, and MongoDB. It supports user authentication, role-based authorization, and route protection for different user roles like `Admin`, `Moderator`, and `Client`. The system ensures secure access and provides role-specific functionality. It also includes persistent session handling, server-side input validation, and dynamic user feedback through flash messages.

## Key Features 🌟

| Feature                | Description                                                      |
|------------------------|------------------------------------------------------------------|
| User Authentication 🔑  | Implemented using Passport.js with local strategy (email and password). |
| Role-Based Authorization ⚖️ | Protects routes for `Admin`, `Moderator`, and `Client` roles.    |
| Persistent Login 🔄      | Session data stored in MongoDB using connect-mongo.              |
| Dynamic Views 🖥️        | Uses EJS templating for server-side rendering of dynamic pages.  |
| Input Validation ✅      | Ensures secure and sanitized user input.                         |
| Flash Messages 💬        | Displays success or error messages during user interaction.      |
| Error Handling 🚫        | Provides custom error pages for HTTP errors like 404 Not Found. |

## Technologies Used ⚙️

| Technology   | Purpose                                                                      |
|---------------|------------------------------------------------------------------------------|
| Express.js    | Backend web framework for building the server, routing, and middleware integration. |
| EJS           | Templating engine for generating dynamic HTML from the server.              |
| Passport.js   | Middleware for handling user authentication and managing sessions securely.|
| MongoDB       | Database for storing user data and session information.                     |
| Mongoose      | ODM for interacting with MongoDB using models and schemas.                  |
| CSS           | For styling and designing the user interface (optional: Tailwind, Bootstrap, or other frameworks). |

## Screenshots 📸

### Admin Page
![Admin Page Screenshot](https://raw.githubusercontent.com/ShantanuKH/rolematrix/refs/heads/main/screenshots/admin.png?token=GHSAT0AAAAAACY7XNLXJMSIXFSWPQIA25BIZ2CDHFQ)

### Home Page
![Home Page Screenshot](https://raw.githubusercontent.com/ShantanuKH/rolematrix/refs/heads/main/screenshots/home.png?token=GHSAT0AAAAAACY7XNLXPFLNJE6A5SY3BLREZ2CDHOA)

### Login Page
![Login Page Screenshot](https://raw.githubusercontent.com/ShantanuKH/rolematrix/refs/heads/main/screenshots/login.png?token=GHSAT0AAAAAACY7XNLWWHDJVAFFB3ZRRY7KZ2CDHQQ)

### Manage User Page
![Manage User Page Screenshot](https://raw.githubusercontent.com/ShantanuKH/rolematrix/refs/heads/main/screenshots/manageUser.png?token=GHSAT0AAAAAACY7XNLWUWXG4AVQZYNZOUUQZ2CDHSQ)

### Profile Page
![Profile Page Screenshot](https://raw.githubusercontent.com/ShantanuKH/rolematrix/refs/heads/main/screenshots/profile.png?token=GHSAT0AAAAAACY7XNLXJYEQXOTBS3ASRVLIZ2CDHVQ)

### Register Page
![Register Page Screenshot](https://raw.githubusercontent.com/ShantanuKH/rolematrix/refs/heads/main/screenshots/register.png?token=GHSAT0AAAAAACY7XNLX2MO556UQ6WEKICZ2Z2CDH2A7)

### Admin Profile
![Admin Profile Screenshot](https://raw.githubusercontent.com/ShantanuKH/rolematrix/refs/heads/main/screenshots/adminProfile.png?token=GHSAT0AAAAAACY7XNLX6EOWXLSMENZMXXKKZ2CDKIQ)

## Author ✍️

**Name:** Shantanu Khadse  
**GitHub:** [ShantanuKH](https://github.com/ShantanuKH)  
**Email:** [shantanukhadse784@gmail.com](mailto:shantanukhadse784@gmail.com)  
**LinkedIn:** [shantanukhadse](https://www.linkedin.com/in/shantanukhadse-a62585230/)
