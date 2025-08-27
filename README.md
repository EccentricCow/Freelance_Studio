# Web Studio Admin Platform

**Web Studio Admin Platform** is a Single Page Application (SPA) built with **Vanilla JavaScript** and the **AdminLTE template (Bootstrap-based)**.  
It provides an easy-to-use interface for managing studio clients, freelancers, and orders.

---

## Purpose

The platform is designed to present orders and employee activities in a clear and structured way.  
It helps administrators track the entire workflow of the web studio:

1. A client creates an order  
2. The administrator registers a freelancer (if not already created)  
3. The administrator creates an order and assigns it to a freelancer  
4. The workflow and progress can be monitored via the admin panel  

---

## Features

- **User-friendly UI** with AdminLTE and Bootstrap
- **CRUD operations** for managing:
  - Freelancers
  - Clients
  - Orders
- **Order management workflow**:
  - Create new orders
  - Assign freelancers to orders
  - Track order progress
- **Database integration with MongoDB**
- **SPA structure**: dynamic content loading without page reloads

---

## Technologies

- **Frontend:**  
  - Vanilla JavaScript  
  - AdminLTE template (Bootstrap 4/5)  

- **Backend & Database:**  
  - Node.js + Express (if used for API)  
  - MongoDB for data persistence  

---

## Installation

### Backend

1. Navigate to the backend folder:
```bash
cd backend
```
2. Install dependencies:
```bash
npm install
```
3. Install migrate-mongo globally:
```bash
npm install -g migrate-mongo
```
4. Run database migrations:
```bash
migrate-mongo up
```
5. Start the backend server:
```bash
npm start
```

### Frontend

1. Navigate to the frontend folder:
```bash
cd frontend
```
2. Install dependencies:
```bash
npm install
```
3. Start the Angular application:
```bash
npm run dev
```

---

### Usage

1. Start the backend server.
2. Open the SPA in your browser.
3. Use the admin dashboard to:
   - add freelancers
   - add clients
   - create and manage orders
   - assign freelancers to orders
