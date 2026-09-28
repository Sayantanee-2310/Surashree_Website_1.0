# Surashree_Website_1.0
 
🏢 Residential Flat & Service Charge Management System

A modern, full-stack **Residential Flat & Service Charge Management System** designed to simplify the management of residential communities, monthly service charges, resident information, payments, notices, and community activities.

The platform provides separate **Admin and Resident dashboards**, secure authentication, online service-charge payments, automatic invoice generation, notice management, and a community gallery — all through a clean and responsive interface.

---

## ✨ Key Features

🔐 Authentication & Role Management

* Secure Admin and Resident login
* Role-based access control
* Protected dashboards and routes
* Residents can access only their own information
* Admin has centralized management access

👨‍💼 Admin Dashboard

* Manage residents and flat information
* Manage monthly service charges
* Monitor payment status of all residents
* View successful, pending, failed, and overdue payments
* View transaction details and payment dates
* Manage notices and announcements
* Upload and manage community/gallery photos
* View payment statistics and collection summaries

👤 Resident Dashboard

* View personal and flat information
* View current service charge and outstanding balance
* Make online service-charge payments
* View complete payment history
* Track payment status
* Access previous payment records
* Download invoices for successful payments
* View notices and community updates

💳 Payment Management

* Online service-charge payment
* Secure payment verification
* Support for common Indian payment methods depending on the configured gateway
* Automatic payment-status updates
* Duplicate-payment protection
* Transaction ID tracking
* Complete payment history

🧾 Automatic Invoice Generation

After a successful payment, the system automatically generates a professional PDF invoice containing:

* Invoice number
* Resident name
* Flat number
* Billing month
* Service-charge amount
* Payment date
* Transaction ID
* Payment status

Residents can access and download invoices directly from their payment history.

📢 Notice Management

Administrators can:

* Create notices
* Edit notices
* Delete notices
* Publish important announcements
* Share community updates with residents

🖼️ Community Gallery

* Upload residential community photos
* Festival and celebration photos
* Event photographs
* Admin-controlled gallery management
* Responsive image display

---

## 🎨 Design & User Experience

The application is designed with a **premium, modern, and distinctive visual style** rather than following a conventional property-management template.

### Design principles

* Modern and minimal interface
* Responsive design
* Clean typography
* Interactive dashboard components
* Subtle animations and transitions
* Elegant cards and data tables
* Modern payment interface
* Structured information architecture
* Mobile, tablet, and desktop support

The goal is to create an application that feels like a **real-world residential management platform**, rather than a generic generated dashboard.

---

## 🛠️ Technology Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Responsive UI

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB

### Authentication

* JWT-based authentication
* Role-based authorization
* Protected API routes

### Payment

* Payment gateway integration
* Server-side payment verification
* Transaction management

### Documents

* Dynamic PDF invoice/receipt generation

### Development Tools

* Git
* GitHub
* npm

---

## 🗂️ Main Modules

```text
Residential Management System
│
├── Authentication
│   ├── Admin Login
│   └── Resident Login
│
├── Admin Dashboard
│   ├── Residents
│   ├── Flats
│   ├── Service Charges
│   ├── Payments
│   ├── Notices
│   └── Gallery
│
├── Resident Dashboard
│   ├── Profile
│   ├── Service Charges
│   ├── Payment
│   ├── Payment History
│   └── Invoices
│
├── Payment System
│   ├── Payment Processing
│   ├── Verification
│   ├── Transactions
│   └── Invoice Generation
│
└── Community
    ├── Notices
    └── Gallery
```

---

## 🔒 Security

The system follows standard application-security practices, including:

* Password-protected authentication
* JWT-based session management
* Role-based authorization
* Protected API endpoints
* Input validation
* Secure payment verification
* Duplicate transaction prevention
* Restricted access to resident-specific information

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd residential-management-system
```

### 2. Install dependencies

For the frontend:

```bash
npm install
```

For the backend, if maintained separately:

```bash
cd backend
npm install
```

### 3. Configure environment variables

Create a `.env` file and configure the required values:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secure_jwt_secret

PAYMENT_KEY_ID=your_payment_gateway_key
PAYMENT_KEY_SECRET=your_payment_gateway_secret
```

Use the actual variable names required by the implementation.

### 4. Start the application

Frontend:

```bash
npm run dev
```

Backend:

```bash
npm run server
```

or use the project's configured start scripts.

---

## 🔄 Application Flow

### Resident

```text
Login
  ↓
Resident Dashboard
  ↓
View Service Charge
  ↓
Pay Online
  ↓
Payment Verification
  ↓
Payment Successful
  ↓
Invoice Generated
  ↓
Download Invoice
```

### Admin

```text
Admin Login
  ↓
Admin Dashboard
  ↓
Manage Residents & Flats
  ↓
Manage Service Charges
  ↓
Monitor Payments
  ↓
Manage Notices
  ↓
Manage Gallery
```

---

## 📊 Payment Status

The system can maintain payment states such as:

| Status     | Description                                               |
| ---------- | --------------------------------------------------------- |
| Pending    | Payment has not yet been completed                        |
| Successful | Payment has been verified successfully                    |
| Failed     | Payment attempt was unsuccessful                          |
| Overdue    | Payment has not been completed within the required period |

---

## 🚀 Future Enhancements

Potential future improvements include:

* Automated monthly bill generation
* Email/SMS payment notifications
* WhatsApp notifications
* Maintenance complaint management
* Visitor management
* Emergency contact system
* Community polls
* Expense management
* Maintenance staff management
* Advanced financial reports
* Automated payment reminders
* Multi-building support
* Cloud deployment and automated backups

---

## 📌 Project Objective

The primary objective of this project is to replace manual residential service-charge management with a **centralized digital platform** where administrators can efficiently manage residents and payments while residents can conveniently view and pay their charges, access invoices, and receive community updates.

---

## 👩‍💻 Project Type

**Full-Stack Web Application**

**Domain:** Residential / Community Management

**Core Modules:** Authentication • Resident Management • Service Charges • Online Payments • Invoices • Notices • Gallery • Admin Dashboard • Resident Dashboard

---

## 📄 License

This project is intended for educational, personal, or organizational use. Add the appropriate license here based on your project's distribution requirements.
