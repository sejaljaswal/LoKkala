# Lokkala

Lokkala is a web platform that promotes local artisans and their handmade products. Users can explore traditional crafts, view artist profiles, and securely purchase authentic handmade items.

**Live Demo:** [https://your-live-demo-link.com ](https://lokkalala.vercel.app/) 
**GitHub Repo:** [https://your-github-repo-link.com](https://github.com/sejaljaswal/Lokkala)

## Features

- **User Authentication & Roles** – Email/password signup and login with JWT-based auth; separate experiences for buyers and artisans.
- **Artisan Profiles** – Detailed profiles with bios, locations, and showcased artworks.
- **Product Catalog** – Browse, filter, and search curated handmade items with rich metadata (images, categories, materials, price).
- **Cart & Checkout** – Add items to cart, manage quantities, and complete orders with shipping details.
- **Payments** – Secure online payments powered by Razorpay, with support for COD as needed.
- **Media Management** – Product and profile images uploaded and served via Cloudinary.
- **Order Management** – Track order status and history for both buyers and artisans.

## Tech Stack

- **Frontend**: Next.js (App Router), React, TypeScript, Tailwind CSS  
- **Backend**: Next.js API routes (Node.js), JWT-based authentication  
- **Database**: MongoDB with Mongoose ODM  
- **Payments**: Razorpay Payment Gateway  
- **Media Storage**: Cloudinary  
- **Tooling**: ESLint, TypeScript, npm

## Project Structure (high-level)

- `app/` – Next.js App Router pages and layouts  
- `app/api/` – API routes for auth, products, orders, payments, etc.  
- `components/` – Reusable UI components  
- `lib/` or `utils/` – Helpers (e.g., DB connection, auth utilities, payment helpers)  
- `models/` – Mongoose models for users, products, orders, etc.  
- `public/` – Static assets  
- `styles/` – Global styles / Tailwind config  
- `env` – Environment variables (configured via `.env.local`)


## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- npm or yarn
- MongoDB instance (local or hosted, e.g. MongoDB Atlas)
- Razorpay account (API keys)
- Cloudinary account (cloud name, API key/secret)

### Clone and Install

```bash
git clone <YOUR_REPO_URL> lokkala
cd lokkala
npm install
# or
yarn install
