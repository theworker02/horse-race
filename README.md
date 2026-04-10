# Horse Race Game 🏇

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/yourusername/horse-race/releases/tag/v1.0.0)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react)](https://reactjs.org/)
[![Node](https://img.shields.io/badge/Node-18+-339933?logo=node.js)](https://nodejs.org/)

A thrilling horse racing simulator built with React. Place bets, watch horses race in real-time, and track your winnings. Features dynamic weather, bold bet multipliers, and live race analytics.

## 🎮 Features

- **Real-time Race Simulation** — Watch horses race with physics-based speed calculations
- **Dynamic Betting System** — Adjust bet amounts and select your horse
- **Bold Bet Mode** — 3× payout multiplier with increased difficulty
- **Weather Effects** — Sunny, cloudy, rainy, and muddy conditions impact race outcomes
- **Live Statistics** — Win rate, total winnings, and race history tracking
- **Mobile-First Design** — Fully responsive with touch gestures (pull-to-refresh)
- **Smooth Animations** — Framer Motion-powered transitions and effects

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/horse-race.git
cd horse-race

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be available at `http://localhost:5173`

## 🐳 Docker Deployment

### Build the Docker Image

```bash
docker build -t horse-race:v1.0.0 .
```

### Run the Container

```bash
docker run -p 3000:3000 horse-race:v1.0.0
```

Access the app at `http://localhost:3000`

## 📱 Available on

- **Web:** [Play Online](https://horse-race.base44.app/)
- **GitHub:** [theworker02/horse-race](https://github.com/theworker02/horse-race)

## 🎯 How to Play

1. **Select a Horse** — Choose your favorite racehorse from the betting panel
2. **Place Your Bet** — Pick an amount from preset options or use custom controls
3. **Optional: Bold Bet** — Toggle for 3× payout (riskier odds)
4. **Race!** — Click "Place Bet & Race" to start
5. **Watch & Win** — See your horse compete in real-time
6. **Check Stats** — View your lifetime performance in the Statistics page

## 🛠️ Tech Stack

- **Frontend:** React 18, Tailwind CSS, Framer Motion
- **State Management:** React Hooks
- **Routing:** React Router v6
- **UI Components:** shadcn/ui, Radix UI
- **Charts:** Recharts
- **Build Tool:** Vite
- **Backend:** Base44 (platform backend)

## 📊 Project Statistics

- Horses in race: 6 unique horses with procedural generation
- Tracks: 100-unit race distance
- Balance: Starting with $10,000 in chips
- Odds Range: 2:1 to 6:1 base odds

## 📝 License

MIT License — see LICENSE file for details

## 👨‍💻 Development

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Code Structure

```
src/
├── pages/           # Page components (HorseRacing, Stats, Settings)
├── components/      # Reusable components
│   ├── racing/     # Race-specific components
│   ├── mobile/     # Mobile-specific components
│   └── ui/         # UI primitives (shadcn/ui)
├── lib/            # Utility functions (race engine, odds, weather)
├── hooks/          # Custom React hooks
└── api/            # API client configuration
```

## 🔗 Links

- **Project Website:** [horse-race.base44.app](https://horse-race.base44.app/)
- **GitHub Repository:** [theworker02/horse-race](https://github.com/theworker02/horse-race)
- **GitHub Release:** [v1.0.0](https://github.com/theworker02/horse-race/releases/tag/v1.0.0)
- **Documentation:** [Wiki](https://github.com/theworker02/horse-race/wiki)

## 🐛 Known Issues & Roadmap

- [ ] Multiplayer racing
- [ ] Leaderboard system
- [ ] Advanced betting strategies
- [ ] Stable ownership mechanics
- [ ] Custom horse breeding

## 💬 Support

For issues and feature requests, please use [GitHub Issues](https://github.com/yourusername/horse-race/issues).

---

**Made with ❤️ using React & Base44`