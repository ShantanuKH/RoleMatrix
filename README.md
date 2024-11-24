# RoleMatrix - RBAC Project 🛡️🔐

## Overview 📚
RoleMatrix is a full-stack implementation of **Role-Based Access Control (RBAC)** designed to manage user authentication, role-based authorization, and secure route protection for roles such as `Admin`, `Moderator`, and `Client`. The project ensures secure access, persistent sessions, and server-side input validation, with dynamic user feedback via flash messages.

---

## Key Features 🌟

| Feature                | Description                                                        |
|------------------------|--------------------------------------------------------------------|
| **User Authentication** 🔑  | Powered by Passport.js with a local strategy (email and password). |
| **Role-Based Authorization** ⚖️ | Protects routes based on roles (`Admin`, `Moderator`, `Client`).   |
| **Persistent Login** 🔄      | Sessions stored in MongoDB using `connect-mongo`.             |
| **Dynamic Views** 🖥️        | Server-side rendering with EJS templating.                     |
| **Input Validation** ✅      | Secure, sanitized user input handling.                         |
| **Flash Messages** 💬        | Displays user interaction feedback (success or error).         |
| **Error Handling** 🚫        | Custom error pages for HTTP errors like 404 Not Found.         |

---

## Technologies Used ⚙️

| Technology     | Purpose                                                                      |
|-----------------|------------------------------------------------------------------------------|
| **Express.js**  | Backend web framework for building the server, routing, and middleware.     |
| **EJS**         | Templating engine for server-side rendering of dynamic HTML.                |
| **Passport.js** | Middleware for handling authentication and managing sessions.               |
| **MongoDB**     | Database for storing user and session data.                                 |
| **Mongoose**    | ODM for defining and interacting with MongoDB collections.                  |
| **CSS**         | For designing the user interface (optionally with Tailwind or Bootstrap).   |

---

## Screenshots 📸

<table>
<tr>
<th>Page</th>
<th>Screenshot</th>
<th>Page</th>
<th>Screenshot</th>
</tr>
<tr>
<td><strong>Admin Page</strong></td>
<td><img src="https://raw.githubusercontent.com/ShantanuKH/rolematrix/main/screenshots/admin.png" width="350"></td>
<td><strong>Home Page</strong></td>
<td><img src="https://raw.githubusercontent.com/ShantanuKH/rolematrix/main/screenshots/home.png" width="350"></td>
</tr>
<tr>
<td><strong>Login Page</strong></td>
<td><img src="https://raw.githubusercontent.com/ShantanuKH/rolematrix/main/screenshots/login.png" width="350"></td>
<td><strong>Manage User Page</strong></td>
<td><img src="https://raw.githubusercontent.com/ShantanuKH/rolematrix/main/screenshots/manageUser.png" width="350"></td>
</tr>
<tr>
<td><strong>Profile Page</strong></td>
<td><img src="https://raw.githubusercontent.com/ShantanuKH/rolematrix/main/screenshots/profile.png" width="350"></td>
<td><strong>Register Page</strong></td>
<td><img src="https://raw.githubusercontent.com/ShantanuKH/rolematrix/main/screenshots/register.png" width="350"></td>
</tr>
<tr>
<td><strong>Admin Profile</strong></td>
<td><img src="https://raw.githubusercontent.com/ShantanuKH/rolematrix/main/screenshots/adminProfile.png" width="350"></td>
<td></td>
<td></td>
</tr>
</table>

---

## Admin Account Details

The **Admin** of the RoleMatrix system has full privileges.  
- **Admin Email:** `khadseshsantanu02@gmail.com`  
- Admins can:
  - Manage users (add, update, delete).
  - Assign or modify roles.
  - Ensure the system runs smoothly.

---

## Getting Started

### Prerequisites
Ensure you have the following installed on your system:
- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)
- MongoDB (local or cloud-based)

---

### Clone the Repository
To clone the repository, run the following commands:
```bash
git clone https://github.com/ShantanuKH/RoleMatrix.git
cd RoleMatrix
npm install
```
## Environment Setup
Create a .env file in the project root and configure the following variables:

```
MONGO_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
```
## Start Project
```
npm start
```
## Contact Here


   ### Shantanu Khadse
  
  GitHub: [ShantanuKH](https://github.com/ShantanuKH)
  
  Email: shantanukhadse784@gmail.com  
  
  LinkedIn: [shantanukhadse](https://www.linkedin.com/in/shantanu-khadse-a62585230/)
  









