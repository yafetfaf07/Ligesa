<div align="center">

# 🌍 Ligesa  
### Helping communities give smarter — transparent, secure, and digital.

A modern QR-based digital charity platform enabling secure, cashless, and trustworthy donations using **ArifPay**.  
Built to support Ethiopia’s transition toward a **digitally empowered, transparent giving culture**.

</div>

---

## ✨ Overview

**Ligesa** simplifies how donations are collected and managed by enabling churches, mosques, NGOs, and community groups to receive contributions via **QR code payments**.

This reduces:
- Cash handling risks ✅
- Manual counting & recording ✅
- Lack of transparency ✅

And ensures:
- Trust  
- Efficiency  
- Real-time accountability  

---

## 🚀 Features

| Feature Category | Description |
|---|---|
| **QR Donation** | Generate & scan donation QR codes instantly. |
| **Real-Time Ledger** | Every donation is logged transparently & securely. |
| **Diaspora Support** | Donors abroad can give without friction. |
| **Role-Based Access** | Separate donor/admin/organization panels. |
| **Cross-Platform Mobile UI** | Works seamlessly on Android & iOS via Flutter. |

---

## 📱 App Screenshots (Actual UI)

<div align="center">

| | | |
|---|---|---|
| **Onboarding** | **Welcome UI** | **Secure Login** |
| <img src="./screenshots/onboarding1.png" width="250"/> | <img src="./screenshots/onboarding2.png" width="250"/> | <img src="./screenshots/onboarding3.png" width="250"/> |

</div>

> *(More screens can be added for Home → QR Scan → Donation Flow once available.)*

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Mobile App | **Flutter + Dart** |
| Backend API | **Node.js + Express** |
| Database | **PostgreSQL** |
| Payments | **ArifPay API** |
| Auth | **JWT Access & Refresh Tokens** |

---

## ⚙️ Setup Instructions

### 1️⃣ Backend Setup

```bash
git clone <your-backend-repo>
cd ligesa-backend
npm install
npm run dev
```

Server runs at:
```
http://localhost:5000
```

### 2️⃣ Flutter App Setup

```bash
cd ../ligesa-frontend
flutter pub get
flutter run
```

---

## 🔐 Environment Variables

### Backend `.env` Example
```
PORT=5000
JWT_ACCESS_SECRET=YOUR_SECRET_KEY
JWT_REFRESH_SECRET=YOUR_REFRESH_KEY
DATABASE_URL="postgresql://user:password@localhost:5432/ligesa"
```

### Flutter App Config Example
```
ARIFPAY_TOKEN=YOUR_ARIFPAY_LIVE_KEY
```

> **Never commit real tokens.**

---

## 🌍 Vision & Impact

Ligesa promotes:
- Transparency in charitable donations  
- Financial inclusion  
- Trust between donors & institutions  
- Growth of Ethiopia’s digital economy  

---

## 🤝 Contributing

Pull requests, feature suggestions, and collaboration discussions are welcome.

---

<div align="center">

**Built with ❤️ to make generosity simple, secure, and transparent.**

</div>