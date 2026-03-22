# Sanguine

Sanguine is a web-based blood donation and request management system that connects clients, hospitals, and administrators through a centralized platform.

---

## Overview

Sanguine enables users to request blood, manage donor information, and monitor eligibility through a role-based system. 
The application is deployed online and accessible through any modern web browser in any pc.

---

## Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Backend: Node.js (Express)  
- Database: PostgreSQL (Supabase)  
- Authentication: JWT (JSON Web Tokens)  

---

## Project Structure

ProjectSanguine/

backend/
- db.js              # PostgreSQL connection  
- server.js          # Express server and API routes  
- package.json  
- .env  

frontend/
- admin/             # Admin pages  
- hospital/          # Hospital pages  
- user/              # Client pages  
- css/               # Stylesheets  

- login.html         # Login page  
- register.html      # Registration page  

- login.js           # Login API handling  
- register.js        # Registration logic  
- auth.js            # Route protection (JWT)  
- logout.js          # Logout handling  
- profile.js         # Profile data fetching  

vercel.json          # Deployment configuration  
package.json  
.gitignore  

---

## System Architecture

Sanguine follows a three-tier architecture:

Frontend  
Handles user interface and interactions using HTML, CSS, and JavaScript.

Backend  
Built with Node.js and Express, it provides REST APIs and handles authentication and business logic.

Database  
PostgreSQL (via Supabase) stores users, roles, and system data.

---

## Features

- User authentication using JWT  
- Role-based access (Client, Hospital, Admin)  
- Blood request system  
- Profile management  
- Eligibility tracking  

---

## Deployment

Sanguine is deployed as a web application and can be accessed through a browser.

https://project-sanguine.vercel.app

---

## How to Use

1. Open the deployed website  
2. Register or log in  
3. Access features based on role  

Client:
- View and update profile  
- Request blood  
- Check eligibility  

Hospital:
- Manage donor information  
- Handle blood requests
- Request Blood
- View Clients in district for emergency contact  

Admin:
- Monitor and manage users
- Creating new hospitals
- Head Admin creates new admins and can delete them. 
