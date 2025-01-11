# Backoffice Management System - MyManager

## Overview

This project is a **simplified version** of a backoffice management system designed for small businesses to manage products, inventory, customers, and suppliers. While it captures the core functionalities, it is not the complete implementation of a full-scale project. Instead, it serves as a prototype to demonstrate the concept and structure of such a system.

## Features

### 1. User Authentication
- A basic login page that validates credentials to grant access to the system.
- Authentication is simple and hardcoded for demonstration purposes.

### 2. Dashboard
- Displays key statistics such as:
  - Product quantities and stock levels.
  - Number of customers by city.
  - Suppliers per product.

### 3. Side Navigation Bar
- Quick access to major sections:
  - Dashboard
  - Product Management
  - Inventory Management
  - Customer Management
  - Supplier Management
  - Logout

### 4. Product Management
- Add, edit, and remove products.
- Manage product details like name, price, and image.

### 5. Inventory Management
- Track and update product stock levels in real-time.

### 6. Customer Management
- Add, view, and edit customer information.
- Organize customers by city.

### 7. Supplier Management
- Add and manage supplier details.
- Link suppliers to the products they provide.

### 8. Data Persistence
- Uses `localStorage` to store data temporarily in the browser.
- Ensures data remains consistent across page reloads.

### 9. Responsive Design
- Accessible on both desktop and mobile devices.

## Limitations
- This is a **simplified prototype**, not a complete production-ready solution.
- Data is stored in the browser's `localStorage`, which is not suitable for large-scale or long-term data storage.
- Authentication is basic and not secure.

## Technologies Used
- **HTML5**: Structuring content and forms.
- **CSS3**: Styling and responsive design.
- **JavaScript**: Adding interactivity and managing data.
- **localStorage**: Temporary data storage in the browser.
- **FileReader API**: Handling file uploads (e.g., product images).

## Future Enhancements
- Integrate a backend system with a database (e.g., MySQL, MongoDB) for robust data management.
- Implement advanced user authentication methods (e.g., JWT, OAuth).
- Add user roles with specific permissions (e.g., Admin, Manager, Employee).
- Provide real-time analytics and data visualization (charts, graphs).
- Expand to support multiple users and businesses.

## How to Run
1. Clone or download the repository.
2. Open `index.html` in a web browser.
3. Use the login credentials provided in the code to access the system. 

## Disclaimer
This project is intended for learning and demonstration purposes only. It is not designed for use in a production environment.

---

Feel free to contribute to this project or adapt it to your specific needs. For suggestions or feedback, contact nisrineregragui10@gmail.com
