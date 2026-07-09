🚀 OfferBridge – Credit Card Rewards Marketplace

OfferBridge is a peer-to-peer marketplace that enables credit card holders to monetize their unused rewards, cashback, and exclusive offers while helping buyers save money on purchases through secure, escrow-based transactions.

🌐 Live Demo: https://www.gozivo.in

📌 Overview

Credit card holders often have valuable offers that expire unused, while many shoppers miss out on discounts because they don't own eligible cards.

OfferBridge bridges this gap by creating a secure marketplace where:

💳 Cardholders can earn by sharing their card benefits.
🛍️ Buyers can access exclusive discounts and cashback.
🔒 Transactions are protected using an escrow-based payment system.
✨ Features
👤 Buyer
Create purchase requests
Browse available card offers
Secure escrow payment system
Real-time order tracking
Instant notifications
View transaction history
💳 Cardholder
List credit card offers
Accept buyer requests
Manage active transactions
Earn commission on completed orders
Dashboard with transaction history
🛠 Admin
User management
Transaction monitoring
Marketplace analytics
Dispute handling
Platform overview
⚙️ How It Works
Buyer Flow
Register an account
Create a purchase request
Browse matching card offers
Select the best offer
Deposit payment into escrow
Track the order
Confirm delivery
Cardholder Flow
Register and verify account
Add credit card information
Publish available offers
Accept buyer requests
Complete the purchase using the card
Upload tracking details
Receive payment after successful completion
🔄 Transaction Flow
Buyer
   │
Create Request
   │
Choose Card Offer
   │
Deposit Payment (Escrow)
   │
Cardholder Purchases Item
   │
Tracking Details Shared
   │
Buyer Confirms Delivery
   │
Escrow Releases Payment
🛠 Tech Stack
Frontend
Next.js
React
Tailwind CSS
Framer Motion
Recharts
Backend
Node.js
Next.js API Routes
Database
MongoDB Atlas
Mongoose
Authentication
NextAuth.js
JWT
Google OAuth
GitHub OAuth
Payments
Stripe
Other Tools
SendGrid
WebSockets
Git
GitHub
Vercel
🔐 Security
JWT Authentication
Password hashing using bcrypt
Role-Based Access Control (RBAC)
HTTPS
Environment variable management
Input validation
Secure session handling
📂 Project Structure
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
├── lib
│   ├── api.js
│   ├── authContext.js
│   ├── config.js
│   ├── logger.js
│   ├── models.js
│   └── mongodb.js
🚀 Getting Started
Clone the repository
git clone https://github.com/yourusername/OfferBridge.git
Navigate to the project
cd OfferBridge
Install dependencies
npm install
Create a .env.local
MONGODB_URI=
NEXTAUTH_SECRET=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=
STRIPE_SECRET_KEY=
SENDGRID_API_KEY=
Run the project
npm run dev

Visit

http://localhost:3000
📡 API Routes
Authentication
POST /api/auth
GET /api/auth/[...nextauth]
Requests & Offers
GET    /api/data
POST   /api/data
PATCH  /api/data
DELETE /api/data
Payments
GET  /api/payment
POST /api/payment
PUT  /api/payment
Notifications
GET   /api/notifications
PATCH /api/notifications
📈 Future Enhancements
📱 Android & iOS apps
🤖 AI-powered offer matching
🌍 Multi-currency support
📊 Advanced analytics dashboard
🔔 Push notifications
💬 In-app messaging
🌐 International expansion
🤝 Contributing

Contributions are welcome!

Fork the repository
Create a feature branch
Commit your changes
Push your branch
Open a Pull Request
📄 License

This project is licensed under the MIT License.

👨‍💻 Author

GoZivo Team

🌐 https://www.gozivo.in
