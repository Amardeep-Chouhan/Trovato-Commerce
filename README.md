# 🛍️ Trovato

A modern full-stack e-commerce platform built with React, TypeScript, Express.js, PostgreSQL, and real-time communication features.

Trovato combines a production-ready shopping experience with secure authentication, payments, customer support chat, video calling, monitoring, and scalable backend architecture.

---
![Demo App](/frontend/public/screenshot-for-readme.png)

## 🚀 Live Demo

🔗 https://trovato-commerce.onrender.com

---

## ✨ Features

### 🛒 E-Commerce

* Product Catalog & Product Details
* Shopping Cart Management
* Secure Checkout Flow
* Order Management System
* Category-Based Product Filtering

### 🔐 Authentication

* Clerk Authentication
* Secure User Sessions
* Protected Routes
* Role-Based Access Control

### 💳 Payments

* Polar Payment Integration
* Webhook Handling
* Order Verification
* Secure Transaction Processing

### 📦 Admin Dashboard

* Product Management
* Product Creation & Updates
* Order Monitoring
* Inventory Control

### 💬 Customer Support

* Real-Time Messaging with Stream
* Typing Indicators
* Message Reactions
* Threaded Conversations
* File Sharing
* GIF Support

### 📹 Video Calling

* One-to-One Video Calls
* Stream Video Integration
* Real-Time Communication

### 📤 Media Management

* Image Uploads
* Image Optimization
* CDN Delivery with ImageKit

### 🚨 Monitoring & Observability

* Error Tracking with Sentry
* Performance Monitoring
* Structured Logging
* Production Debugging Tools

---

## 🏗️ Tech Stack

### Frontend

* React
* TypeScript
* TanStack Query
* React Router
* Tailwind CSS
* DaisyUI
* Clerk

### Backend

* Express.js
* TypeScript
* Drizzle ORM
* PostgreSQL
* Neon Database

### Third-Party Services

* Clerk Authentication
* Polar Payments
* Stream Chat & Video
* ImageKit
* Sentry

---

## 📂 Project Structure

```bash
trovato/
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── src/
│   ├── scripts/
│   └── package.json
│
└── README.md
```

---

## ⚙️ Environment Variables

### Backend (.env)

```env
PORT=5000
NODE_ENV=development

DATABASE_URL=

CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CLERK_WEBHOOK_SECRET=

SENTRY_DSN=

STREAM_API_KEY=
STREAM_API_SECRET=

IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
IMAGEKIT_URL_ENDPOINT=

FRONTEND_URL=

POLAR_ACCESS_TOKEN=
POLAR_WEBHOOK_SECRET=
POLAR_API_BASE=

POLAR_CHECKOUT_PRODUCT_ID=
```

### Frontend (.env)

```env
VITE_CLERK_PUBLISHABLE_KEY=

VITE_SENTRY_DSN=

VITE_API_URL=
```

---

## 🛠️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/trovato.git

cd trovato
```

### Install Dependencies

Frontend

```bash
cd frontend
npm install
```

Backend

```bash
cd backend
npm install
```

### Configure Environment Variables

Create `.env` files inside both frontend and backend folders.

### Run Database Migrations

```bash
npm run db:push
```

### Seed Products

```bash
npm run seed
```

### Start Development Servers

Backend

```bash
npm run dev
```

Frontend

```bash
npm run dev
```

---

## 📸 Screenshots

Add screenshots of:

* Home Page
* Product Page
* Cart
* Checkout
* Admin Dashboard
* Chat System
* Video Calling

---

## 🎯 Key Learning Outcomes

* Full Stack Architecture
* REST API Development
* Authentication & Authorization
* Payment Integration
* Real-Time Communication
* Database Design
* Monitoring & Observability
* Production Deployment
* Third-Party Service Integrations

---

## 🚀 Deployment

Deploy the application using:

* Vercel (Frontend)
* Render / Railway / VPS (Backend)
* Neon (Database)
* Clerk
* Polar
* Stream
* ImageKit
* Sentry

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Pranshu Mishra**

Building modern web applications with scalable architecture and production-ready workflows.
