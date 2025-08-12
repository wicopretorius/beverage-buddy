<p align="center">
  <img src="./assets/beveragebuddy-logo.svg" width="300" alt="BeverageBuddy Logo">
</p>

# 🍹 BeverageBuddy

> A simple React Native + Firebase app for sharing and discovering friends’ drink preferences via QR codes — so you always pour it right.

---

## 📖 About

**BeverageBuddy** makes it easy to remember exactly how your friends and family like their drinks — from coffee and tea to cocktails and craft beer.

Users create **Drink Cards** with their beverage preferences, share them via QR codes, and update them anytime. When you visit someone, their perfect drink order is already in your pocket.

---

## ✨ Features (MVP)

- 📋 **Create & edit Drink Cards** with hot, cold, and alcoholic beverage preferences.
- 📲 **Share via QR code** for instant linking.
- 🔄 **Live updates** — if a friend changes their card, you see it instantly.
- 🔐 **One-way follow system** for privacy (guests don’t see other guests).
- 📱 **Cross-platform**: Works on Android and iOS with Expo.

---

## 🛠️ Tech Stack

- **Frontend:** [React Native](https://reactnative.dev/) (Expo)
- **Backend:** [Firebase](https://firebase.google.com/) (Auth, Firestore, Functions)
- **Other:** QR code generation & scanning, real-time sync

---

## 📦 Installation

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn
- Expo CLI (`npm install -g expo-cli`)

### Steps
```bash
# 1. Clone the repo
git clone https://github.com/YOUR-USERNAME/beverage-buddy.git

# 2. Navigate into the folder
cd beverage-buddy

# 3. Install dependencies
npm install

```
BeverageBuddy/
├── assets/             # Images, logos, icons
├── components/         # Reusable UI components
├── screens/            # App screens (MyDrinks, Friends, ScanQR, etc.)
├── navigation/         # Navigation stack & tab config
├── services/           # Firebase & helper functions
├── App.js              # Entry point
└── README.md

👩‍💻 Author
Wico Pretorius – @wicopretorius


# 4. Start the app
npx expo start
