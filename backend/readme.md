# Pharmacy Management System

A complete pharmacy management system with user registration, login, medicine browsing, shopping cart, and admin panel.

## Features

### User Features
- User registration with username, password, and address
- User login and authentication
- Browse medicines
- Add medicines to shopping cart
- Place orders with delivery address

### Admin Features
- Special admin account (username: Ayman_Mamdouh, password: ASMA#)
- Add new medicines with name, price, and image (now supports file upload)
- View all orders from customers
- Access to admin panel

### UI/UX Improvements
- File input for medicine images instead of URL input
- Updated color scheme (black text on white, white text on black)
- Improved accessibility and contrast

## How to Use

1. Start the server:
   ```bash
   node server.js
   ```

2. Open your browser and navigate to:
   - Main page: http://localhost:3000/Pages/index.html
   - Login page: http://localhost:3000/Pages/login.html
   - Register page: http://localhost:3000/Pages/Resigter.html

3. For admin access:
   - Username: Ayman_Mamdouh
   - Password: ASMA#

## System Architecture

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js with built-in http module (no external dependencies)
- Database: In-memory storage (for demonstration purposes)

## Pages

- **Index**: Main landing page
- **Login**: User authentication
- **Register**: New user registration
- **Medicine**: Browse and purchase medicines
- **Admin**: Admin panel to manage medicines and orders
- **Services**: Information about pharmacy services
- **About**: Information about the pharmacy

## Security

- Passwords are stored in plain text (for demonstration purposes)
- Admin access is determined by username
- CORS enabled for API communication

## File Structure

```
Pharmacy Project/
├── Pages/
│   ├── Resigter.html (New registration page)
│   ├── admin.html (Admin panel)
│   ├── index.html
│   ├── login.html
│   ├── medicine.html
│   ├── services.html
│   └── about.html
├── Scripts/
│   ├── script.js (General scripts)
│   └── Login.js (Login functionality)
├── Styles/
├── Images/
├── server.js (Backend server)
└── README.md
```