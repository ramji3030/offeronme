# OfferOnMe 🎁

> Spread generosity - Send coffee, drinks, and thoughtful gifts instantly

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## 🌟 Overview

OfferOnMe is a social gifting platform that makes it effortless to surprise friends, family, and colleagues with thoughtful gifts anytime, anywhere. Inspired by the power of spontaneous generosity, our platform connects people through instant digital gifts that can be redeemed at local establishments.

## ✨ Key Features

### 🎯 Core Functionality
- **Instant Gifting**: Send menu items or gift cards in seconds
- **SMS Notifications**: Recipients get instant text alerts with redemption links
- **Digital Redemption**: Easy-to-use digital cards for quick redemption
- **Multi-Venue Support**: Partner with bars, restaurants, and cafes

### 💳 Payment & Redemption
- **Secure Payments**: Safe and encrypted transaction processing
- **Virtual Visa Gift Cards**: Non-reloadable virtual gift card options
- **QR Code Redemption**: Fast scanning at partner venues
- **Real-time Balance**: Track gift status and redemption

### 🏪 For Businesses
- **Venue Partnership**: Join our growing network of local businesses
- **Promotion Tools**: In-app marketing and special offers
- **Analytics Dashboard**: Track gift redemptions and customer insights
- **Custom Branding**: Showcase your menu and offerings

### 👥 Social Features
- **Contact Integration**: Easy friend selection from your contacts
- **Occasion Templates**: Birthday, thank you, just because, and more
- **Gift History**: Track sent and received gifts
- **Social Sharing**: Share generosity on social media

## 🚀 How It Works

### For Senders:
1. **Select**: Choose a venue and menu item or gift amount
2. **Personalize**: Add a message and select recipient
3. **Send**: Gift delivered instantly via SMS

### For Recipients:
1. **Receive**: Get SMS notification with gift details
2. **View**: See personalized message and gift info
3. **Redeem**: Present digital card at venue to claim

### For Venues:
1. **Partner**: Sign up and create your venue profile
2. **List**: Add menu items and pricing
3. **Redeem**: Scan customer QR codes to fulfill orders

## 🛠️ Technology Stack

### Frontend (Mobile App)
- **React Native** - Cross-platform mobile development
- **TypeScript** - Type-safe code
- **Redux Toolkit** - State management
- **React Navigation** - Navigation framework

### Backend (API)
- **Node.js** - Server runtime
- **Express.js** - Web framework
- **MongoDB** - Database
- **Stripe API** - Payment processing
- **Twilio API** - SMS notifications

### Infrastructure
- **AWS** - Cloud hosting (EC2, S3, RDS)
- **Docker** - Containerization
- **GitHub Actions** - CI/CD pipeline
- **CloudFlare** - CDN and security

## 📦 Installation

### Prerequisites
```bash
node >= 18.x
npm >= 9.x
mongodb >= 6.x
```

### Clone Repository
```bash
git clone https://github.com/ramji3030/offeronme.git
cd offeronme
```

### Install Dependencies

#### Server Setup
```bash
cd server
npm install
cp .env.example .env
# Configure environment variables
npm run dev
```

#### Client Setup
```bash
cd client
npm install
npx pod-install ios # iOS only
npm run android # or npm run ios
```

## 🏗️ Project Structure

```
offeronme/
├── client/              # React Native mobile app
│   ├── src/
│   │   ├── components/  # Reusable UI components
│   │   ├── screens/     # App screens
│   │   ├── navigation/  # Navigation setup
│   │   ├── store/       # Redux store
│   │   ├── services/    # API services
│   │   └── utils/       # Helper functions
│   └── package.json
├── server/              # Node.js backend
│   ├── src/
│   │   ├── controllers/ # Request handlers
│   │   ├── models/      # Database models
│   │   ├── routes/      # API routes
│   │   ├── middleware/  # Custom middleware
│   │   ├── services/    # Business logic
│   │   └── config/      # Configuration
│   └── package.json
├── docs/                # Documentation
└── .env.example         # Environment template
```

## 🗺️ Development Roadmap

### Phase 1: MVP (Current) ✅
- [x] Basic repository setup
- [ ] User authentication (SMS verification)
- [ ] Gift sending flow
- [ ] Payment integration (Stripe)
- [ ] Venue onboarding
- [ ] QR code redemption

### Phase 2: Enhancement 🚧
- [ ] Push notifications
- [ ] Advanced search and filtering
- [ ] Gift scheduling
- [ ] Group gifting
- [ ] Loyalty rewards program
- [ ] Apple Pay / Google Pay integration

### Phase 3: Scale 📈
- [ ] Multi-city expansion
- [ ] Corporate gifting portal
- [ ] API for third-party integrations
- [ ] Advanced analytics
- [ ] International payments

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact & Support

- **Developer**: Ramji Bharath
- **Email**: ramji3030@users.noreply.github.com
- **GitHub**: [@ramji3030](https://github.com/ramji3030)

## 🙏 Acknowledgments

- Inspired by OneOnMe's vision of spreading generosity
- Built to support local businesses and communities
- Powered by amazing open-source technologies

---

**OfferOnMe** - *Because every moment is an opportunity to share kindness* ☕🍺🎁
