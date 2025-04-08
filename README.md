<div align="center">
  <br />
  <a href="#">
    <img src="assets/readme-logo.png" alt="logo" width="160" height="117">
  </a>

  <h3 align="center">FundLog</h3>

  <p align="center">
    A Next.js app for tracking expenses and visualizing stats. Fully offline, syncs to MongoDB, supports GitHub/Google OAuth, and faithfully mimics iOS using Tailwind and shadcn/ui
    <br />
    <a href="https://fundlog.xmelonekmax.pl"><strong>Open the app »</strong></a>
  </p>
</div>

## Usage


<a href="https://fundlog.xmelonekmax.pl">`multiplayer.xmelonekmax.pl`</a> - Show your server list

<a href="https://fundlog.xmelonekmax.pl/hypixel.net">`multiplayer.xmelonekmax.pl/hypixel.net`</a> - Add the server & show your updated server list

## ✨ Features
* 💸 Log your expenses and view them on interactive charts
* 💱 Add expenses in any currency – automatically converted to your main currency using real-time exchange rates
* 📱 Native iOS-inspired UI for a smooth and familiar experience
* 🔐 Sign in with GitHub or Google via OAuth
* 💾 Works offline as a PWA, with automatic sync to a MongoDB database when online
* 🌍 Multi-language support (Polish and English)

## 🚀 Getting Started

To run the project locally:

1. **Clone the repository:**

```bash
git clone https://github.com/xMelonekMaX/fund-log.git
cd fund-log
```

2. **Install dependencies:**

```bash
pnpm install
```

3. **Create a `.env` file in the root directory** with the following content:

```env
NEXT_PUBLIC_BASE_URL="http://localhost:3000"

GOOGLE_CLIENT_ID=""
GOOGLE_CLIENT_SECRET=""

GITHUB_CLIENT_ID=""
GITHUB_CLIENT_SECRET=""

MONGODB_URI="mongodb://localhost:27017/fundlog"
```
> ⚠️ Replace the empty values with your actual OAuth credentials.

4. **Build and start the app:**

```bash
pnpm run build
pnpm start
```
The app will be available at [http://localhost:3000](http://localhost:3000)

## 🛠️ Technical Details
* Next.js
* TypeScript
* React Compiler
* next-intl
* ExchangeRate-API
* Serwist
* Arctic
* Mongoose
* MongoDB
* Dexie.js
* Tailwind
* shadcn/ui
