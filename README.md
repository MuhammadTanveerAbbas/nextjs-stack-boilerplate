<div align="center">
  <h1 align="center">My Ultimate Quick Stack ⚡</h1>
  <p align="center">
    A powerful <strong>Next.js boilerplate</strong> integrating <strong>Tailwind CSS</strong>, <strong>MongoDB</strong>, <strong>Auth0</strong>, and <strong>Stripe</strong> the ultimate starting point for full stack web apps.
  </p>
  <div align="center">
    <img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js" height="40" alt="Next.js logo" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" height="40" alt="Tailwind CSS logo" />
    <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" height="40" alt="MongoDB logo" />
    <img src="https://img.shields.io/badge/Auth0-EB5424?style=for-the-badge&logo=auth0&logoColor=white" height="40" alt="Auth0 logo" />
    <img src="https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=stripe&logoColor=white" height="40" alt="Stripe logo" />
  </div>
</div>

---

## 🧩 Overview

**Ultimate Quick Stack** is a production ready **Next.js full stack boilerplate** that brings together the best modern web tools for rapid development.  
Perfect for SaaS products, MVPs, or enterprise grade applications.

---

## ⚙️ Tech Stack

- ⚛️ **Next.js** — React framework for hybrid static & server rendering  
- 🎨 **Tailwind CSS** — Utility first styling for sleek, responsive design  
- 🍃 **MongoDB + Mongoose** — Scalable NoSQL database with elegant schemas  
- 🔐 **Auth0** — Secure, enterprise grade authentication solution  
- 💳 **Stripe** — Seamless payment processing integration  

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/MuhammadTanveerAbbas/nextjs-stack-boilerplate.git
cd nextjs-stack-boilerplate
````

### 2️⃣ Install Dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

### 3️⃣ Configure Environment Variables

Create a `.env.local` file at the project root and add:

```bash
# Auth0
AUTH0_SECRET=
AUTH0_ISSUER_BASE_URL=
AUTH0_CLIENT_ID=
AUTH0_CLIENT_SECRET=
AUTH0_REDIRECT_URI=

# MongoDB
MONGODB_URI=

# Stripe
STRIPE_SECRET_KEY=
STRIPE_PRICE=

# Frontend
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

### 4️⃣ Run the Development Server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Visit ➡️ [http://localhost:3000](http://localhost:3000)

---

## 📦 Folder Structure

```plaintext
/
├── components/       # Reusable React components
├── lib/              # Utility functions and configurations
├── models/           # Mongoose data models
├── pages/            # Next.js page routes
├── public/           # Static assets
├── styles/           # Global CSS & Tailwind configuration
└── .env.local        # Environment variables
```

---

## 🧠 Key Features

* 🔧 Preconfigured **Next.js** environment
* 🌈 Styled with **Tailwind CSS**
* 🧩 Integrated **MongoDB + Mongoose** models
* 🔐 Built in **Auth0 authentication**
* 💳 **Stripe checkout** support
* 🧱 Modular, scalable architecture

---

## 📜 License

Licensed under the **MIT License**.

---

<div align="center">
Made with ❤️ by <strong>Muhammad Tanveer Abbas</strong>
</div>
