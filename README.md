# 🚀 OfferBridge

> A secure peer-to-peer marketplace that enables users to monetize unused credit card rewards while helping others save money through verified card offers and escrow-based transactions.

<p align="center">
  <a href="https://www.gozivo.in">
    <img src="https://img.shields.io/badge/Live-gozivo.in-blue?style=for-the-badge" />
  </a>
  <img src="https://img.shields.io/badge/Next.js-16-black?style=for-the-badge&logo=nextdotjs" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react" />
  <img src="https://img.shields.io/badge/MongoDB-Atlas-47A248?style=for-the-badge&logo=mongodb" />
  <img src="https://img.shields.io/badge/TailwindCSS-3-38B2AC?style=for-the-badge&logo=tailwindcss" />
</p>

---

# 📖 Overview

OfferBridge is a marketplace where credit card holders can earn money by sharing their unused cashback, reward points, and exclusive card offers.

Buyers who don't own premium cards can securely access these discounts through an escrow-based transaction system.

The platform provides:

- 💳 Secure escrow payments
- 🔒 Verified users
- ⚡ Real-time transaction tracking
- 📈 Transparent marketplace
- 🤝 Fair matching between buyers and cardholders

---

# ✨ Features

## 👤 Buyer

- Create purchase requests
- Browse available offers
- Secure escrow payment
- Live order tracking
- Transaction history
- Instant notifications

---

## 💳 Cardholder

- Publish card offers
- Accept purchase requests
- Manage active transactions
- Earn commissions
- Dashboard & analytics

---

## 🛠 Admin

- User management
- Transaction monitoring
- Marketplace analytics
- Dispute handling
- Revenue dashboard

---

# 🔄 Workflow

```text
Buyer
   │
   ▼
Create Purchase Request
   │
   ▼
Browse Card Offers
   │
   ▼
Choose Best Offer
   │
   ▼
Escrow Payment
   │
   ▼
Cardholder Purchases Item
   │
   ▼
Tracking Details Shared
   │
   ▼
Buyer Confirms Delivery
   │
   ▼
Payment Released
```

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Frontend | Next.js, React, Tailwind CSS, Framer Motion |
| Backend | Node.js, Next.js API Routes |
| Database | MongoDB Atlas |
| Authentication | NextAuth.js, JWT, Google OAuth, GitHub OAuth |
| Payments | Stripe |
| Notifications | WebSockets, SendGrid |
| Deployment | Vercel |

---

# 🔐 Security

- JWT Authentication
- Role Based Access Control (RBAC)
- Password Hashing (bcrypt)
- HTTPS Encryption
- Secure Session Management
- Input Validation
- Environment Variables

---

# 📂 Folder Structure

```text
src
│
├── app
│   ├── api
│   ├── layout.js
│   ├── page.js
│   └── globals.css
│
├── components
│   ├── admin
│   ├── auth
│   ├── buyer
│   ├── cardholder
│   ├── landing
│   ├── prosumer
│   └── shared
│
└── lib
    ├── api.js
    ├── authContext.js
    ├── config.js
    ├── logger.js
    ├── models.js
    └── mongodb.js
```

---

# 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/yourusername/OfferBridge.git
```

### Navigate into the project

```bash
cd OfferBridge
```

### Install dependencies

```bash
npm install
```

### Configure environment variables

Create a `.env.local` file:

```env
MONGODB_URI=

NEXTAUTH_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=

STRIPE_SECRET_KEY=

SENDGRID_API_KEY=
```

### Start the development server

```bash
npm run dev
```

Visit:

```
http://localhost:3000
```

---

# 📡 API

## Authentication

```
POST /api/auth
GET  /api/auth/[...nextauth]
```

## Data

```
GET    /api/data
POST   /api/data
PATCH  /api/data
DELETE /api/data
```

## Payments

```
GET  /api/payment
POST /api/payment
PUT  /api/payment
```

---

# 🌱 Future Improvements

- 📱 Android & iOS App
- 🤖 AI-powered offer recommendations
- 🌍 Multi-currency support
- 📊 Advanced analytics
- 💬 In-app messaging
- 🔔 Push notifications

---

# 🤝 Contributing

Contributions are always welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Developed By

**GoZivo Team**

🌐 https://www.gozivo.in

---

⭐ If you found this project useful, don't forget to give it a **Star**!
