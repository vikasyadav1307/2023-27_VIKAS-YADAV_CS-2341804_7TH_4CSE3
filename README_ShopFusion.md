# 🛍️ ShopFusion

### Where Shopping Meets Innovation

**ShopFusion** is a modern e-commerce platform designed to deliver a seamless, responsive, and visually engaging online shopping experience. The platform brings product discovery, category browsing, search, saved products, cart management, authentication, and checkout into one polished storefront.

<p align="center">
  <a href="https://shopfusion-alpha.vercel.app/">
    <img src="https://img.shields.io/badge/🌐_Live_Demo-ShopFusion-7C3AED?style=for-the-badge" alt="Live Demo">
  </a>
  <a href="https://github.com/vikasyadav1307/shopfusion">
    <img src="https://img.shields.io/badge/💻_Source_Code-GitHub-111827?style=for-the-badge&logo=github" alt="Source Code">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js" alt="Next.js">
  <img src="https://img.shields.io/badge/React-19-149ECA?style=flat-square&logo=react" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=flat-square&logo=tailwindcss" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Prisma-ORM-2D3748?style=flat-square&logo=prisma" alt="Prisma">
  <img src="https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=flat-square&logo=postgresql" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Clerk-Authentication-6C47FF?style=flat-square" alt="Clerk">
  <img src="https://img.shields.io/badge/Vercel-Deployed-black?style=flat-square&logo=vercel" alt="Vercel">
</p>

---

## ✨ About the Project

ShopFusion is a full-stack e-commerce web application built around a clean, modern shopping experience.

The interface focuses on:

- 🛍️ Product discovery and browsing
- 🔎 Product search
- 🗂️ Category-based shopping
- ❤️ Saved products
- 🛒 Cart management
- 🔐 User authentication and account management
- 💳 Checkout flow
- 📱 Responsive design
- 📧 Newsletter subscription
- 🚚 Delivery and shopping-service information

The project was developed as a **Summer Internship Project** with an emphasis on modern web development, reusable components, database integration, authentication, and deployment.

---

## 🎯 Project Objectives

| Objective | Description |
|---|---|
| 🛒 Modern Shopping | Create a clean and intuitive online shopping experience |
| 📱 Responsive UI | Provide a consistent experience across desktop and mobile screens |
| 🔐 Authentication | Provide account and authentication functionality |
| 🗄️ Data Management | Connect the application to a relational database through Prisma |
| ⚡ Modern Architecture | Use Next.js App Router and modern React patterns |
| 🌐 Deployment | Deploy the application for real-world access |

---

## 🚀 Key Features

### 🏠 Modern Home Page
A visually rich landing page with featured products, shopping categories, promotional sections, and a guided shopping journey.

### 🔎 Search & Product Discovery
Users can search for products and explore the available catalogue through the storefront.

### 🗂️ Categories & Filters
Products are organized into categories with filtering options that help users narrow down the catalogue.

### ❤️ Saved Products
Users can save products for later access directly from the storefront.

### 🛒 Shopping Cart
The cart allows users to review selected products, change quantities, remove items, and view the order total before checkout.

### 🔐 User Account
Authentication and account management are handled using **Clerk**, including profile and connected-account functionality.

### 💳 Checkout
The application provides a checkout flow from the shopping cart.

### 📧 Newsletter
A newsletter subscription section is included to support product updates and curated content.

### 📱 Responsive Design
The interface is designed to adapt across different screen sizes and devices.

---

## 🖼️ Project Preview

### Home Page

<p align="center">
  <img src="assets/home-page.png" alt="ShopFusion Home Page" width="900">
</p>

### Product Catalogue

<p align="center">
  <img src="assets/product-catalogue.png" alt="ShopFusion Product Catalogue" width="900">
</p>

### Shopping Cart

<p align="center">
  <img src="assets/cart.png" alt="ShopFusion Shopping Cart" width="900">
</p>

### Account & Authentication

<p align="center">
  <img src="assets/account.png" alt="ShopFusion Account" width="900">
</p>

---

## 🧭 User Journey

```text
┌─────────────┐
│   Discover  │
│   Products  │
└──────┬──────┘
       ↓
┌─────────────┐
│ Search /    │
│ Categories  │
└──────┬──────┘
       ↓
┌─────────────┐
│ View Product│
│   Details   │
└──────┬──────┘
       ↓
┌─────────────┐
│ Add to Cart │
│ / Save Item │
└──────┬──────┘
       ↓
┌─────────────┐
│    Cart     │
│   Review    │
└──────┬──────┘
       ↓
┌─────────────┐
│   Checkout  │
└─────────────┘
```

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │       User          │
                    │  Web / Mobile UI    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      Next.js        │
                    │    App Router       │
                    │  React Components    │
                    └───────┬─────┬───────┘
                            │     │
                 ┌──────────┘     └──────────┐
                 ▼                           ▼
        ┌─────────────────┐         ┌─────────────────┐
        │      Clerk      │         │     Prisma      │
        │ Authentication  │         │      ORM        │
        └─────────────────┘         └────────┬────────┘
                                             │
                                             ▼
                                   ┌─────────────────┐
                                   │   PostgreSQL    │
                                   │    Database     │
                                   └─────────────────┘
```

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **Next.js** | Full-stack React framework and application routing |
| **React** | Component-based user interface |
| **TypeScript** | Type-safe application development |
| **Tailwind CSS** | Responsive styling and UI design |
| **Prisma** | ORM and database access |
| **PostgreSQL** | Relational database |
| **Clerk** | Authentication and account management |
| **Vercel** | Application deployment |
| **Git & GitHub** | Version control and source management |

---

## 📁 Project Structure

```text
shopfusion/
│
├── app/             # Next.js App Router pages and routes
├── components/      # Reusable UI components
├── hooks/            # Custom React hooks
├── lib/              # Utility and application logic
├── prisma/           # Prisma schema and database configuration
├── providers/        # Application providers
├── public/           # Static assets
├── scripts/          # Project utility/setup scripts
├── store/            # Application state management
│
├── package.json
├── next.config.js
├── tsconfig.json
└── tailwind.config.*
```

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/vikasyadav1307/shopfusion.git
cd shopfusion
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file and add the required project environment variables.

```env
DATABASE_URL="your_postgresql_connection_string"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your_clerk_publishable_key"
CLERK_SECRET_KEY="your_clerk_secret_key"
```

> Use the environment-variable names provided by the project's existing configuration when setting up the application locally.

### 4. Prepare the database

Run the Prisma migration/database setup required by the project.

```bash
npx prisma migrate dev
```

### 5. Seed the database

```bash
npm run seed
```

### 6. Start the development server

```bash
npm run dev
```

Open the local application in your browser.

### Production

```bash
npm run build
npm run start
```

---

## 🌐 Project Links

| Resource | Link |
|---|---|
| 🌐 **Live Website** | [shopfusion-alpha.vercel.app](https://shopfusion-alpha.vercel.app/) |
| 💻 **Source Code** | [github.com/vikasyadav1307/shopfusion](https://github.com/vikasyadav1307/shopfusion) |

---

## 📚 Internship Documentation

The internship repository also contains:

- 📑 **[Summer Internship Report](./summer-internship-report(vikas).pdf)**
- 📊 **[ShopFusion E-Commerce Platform — Project Presentation](./ShopFusion%20E-Commerce%20Platform%20(1).pdf)**
- 🏆 **[Internship Certificate](./Internship%20certificate.pdf)**

---

## 👨‍💻 Developer

### Vikas Yadav

**B.Tech — Computer Science Engineering**

| Detail | Information |
|---|---|
| 🆔 Roll No. | **CS-2341804** |
| 🏫 Section | **4CSE3** |
| 🎓 Course | **B.Tech — Computer Science Engineering** |

---

## 🎓 Internship Project

**Project:** ShopFusion — E-Commerce Platform  
**Type:** Summer Internship Project  
**Domain:** Full-Stack Web Development

### Key Learning Areas

- Modern Next.js application development
- React component architecture
- TypeScript-based development
- Database integration using Prisma and PostgreSQL
- Authentication using Clerk
- Responsive UI development
- Git/GitHub workflow
- Production deployment using Vercel

---

## ⭐ Acknowledgement

This project was developed as part of my summer internship to gain practical experience in modern full-stack web development and to apply software engineering concepts in a real project environment.

---

<p align="center">
  <strong>🛍️ ShopFusion</strong><br>
  <sub>Where Shopping Meets Innovation</sub>
</p>

<p align="center">
  ⭐ If you find the project interesting, consider starring the repository!
</p>
