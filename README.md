🏠 NaijaHomes

NaijaHomes is a full-stack rental marketplace platform designed to simplify and secure property renting in Nigeria. It connects tenants, landlords, and agents through verified listings, in-app communication, and secure payment systems.

---

🚀 Features

🔐 Authentication

- User registration & login (JWT-based)
- Role-based access (Tenant, Landlord, Agent)

🏠 Property Listings

- Create, view, and manage listings
- Property details with pricing and location
- Image upload support (planned)

💬 Chat System (Planned)

- Real-time communication between users

💳 Payments (Planned)

- Secure rent payments via Paystack
- Escrow-based transaction flow

⭐ Reviews & Ratings (Planned)

- Tenant-to-landlord feedback
- Property ratings

---

🏗️ Tech Stack

Frontend

- Flutter (Dart)
- Material UI

Backend

- Node.js (Express)
- REST API Architecture

DevOps

- GitHub Actions (CI/CD)

---

📂 Project Structure

naijahomes/
│
├── backend/
│   ├── src/
│   │   ├── routes/
│   │   └── server.js
│   └── package.json
│
├── frontend/
│   └── lib/
│       └── main.dart
│
└── .github/
    └── workflows/
        └── ci.yml

---

⚙️ Getting Started

🔹 Backend Setup

cd backend
npm install
npm run dev

Server runs on:

http://localhost:5000

---

🔹 Frontend Setup

cd frontend
flutter pub get
flutter run

---

🔗 API Endpoints (Current)

Auth

POST /api/auth/register
POST /api/auth/login

Listings

GET /api/listings
POST /api/listings

---

🔐 Environment Variables

Create a ".env" file in "/backend":

PORT=5000
JWT_SECRET=your_secret_key
DB_URL=your_database_url
PAYSTACK_SECRET_KEY=your_paystack_key

---

⚙️ CI/CD Pipeline

This project uses GitHub Actions to:

- Install dependencies
- Run backend checks
- Analyze Flutter code

Workflow file:

.github/workflows/ci.yml

---

🚀 Deployment (Planned)

- Backend: AWS / DigitalOcean
- Database: PostgreSQL / MongoDB
- Storage: AWS S3 / Cloudinary

---

🧠 Roadmap

- [ ] Database integration
- [ ] Full authentication system
- [ ] Image upload (Cloudinary/S3)
- [ ] Paystack integration
- [ ] Real-time chat (Socket.io)
- [ ] Admin dashboard

---

🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

📄 License

MIT License

---

👨‍💻 Author

Temitope Alayaki
Frontend Developer | Mobile App Builder

---

💡 Vision

To become Nigeria’s most trusted digital infrastructure for renting homes — eliminating scams, increasing transparency, and simplifying access to housing.

---