# 🎲 Monopoly: Global & Local Edition

A modern, fast-paced, cross-platform digital take on the classic property-trading board game. Built for seamless multiplayer experiences across both mobile and web browsers, this game modernizes the classic mechanics with hyper-localized boards and a frictionless, chat-free gameplay system.

---

## ✨ Key Features

*   **📱 Cross-Platform Play (Web & Mobile):** Fully responsive design allowing you to buy, sell, and trade seamlessly whether you are on a desktop browser or a mobile device.
*   **🌍 Hyper-Localized Boards:** The game dynamically caters to local countries and regions. Instead of generic properties, players can buy and trade real estate relevant to their specific region—ranging from global capitals down to local hubs like Kisumu—making the economic simulation feel close to home.
*   **🔇 Frictionless Multiplayer (No Chat Needed):** Designed for quick, non-toxic gaming sessions. The UI relies entirely on intuitive quick-actions, expressive emotes, and automated trade proposals. There is zero need for text chats or voice discussions to negotiate deals.
*   **⚡ Lightweight & Fast:** Optimized for quick loading and smooth state synchronization between players, ensuring reliable gameplay even on slower mobile networks.

---

## 🛠️ Tech Stack Concept

*   **Frontend:** React / Progressive Web App (PWA) architecture for native-feeling mobile experiences and offline-ready asset loading.
*   **Backend:** Go (Golang) server handling real-time game state, utilizing standard Go packages for high-performance, lightweight execution without unnecessary external frameworks.
*   **Communication:** WebSockets for instant, low-latency multiplayer synchronization.

---

## 🎮 How to Play (The Silent Negotiation System)

Since the game removes the need for voice or text chat, all interactions are handled through our streamlined UI:
1.  **Select a Player:** Tap on an opponent's avatar.
2.  **Propose a Trade:** Use the visual trade builder to drag and drop properties or cash you want to offer and what you want in return.
3.  **Accept/Counter/Reject:** The receiving player gets live visual indicators and can tap to accept, decline, or instantly modify the offer using slider controls.

---

## 🚀 Getting Started

### Prerequisites
*   [Go](https://golang.org/) (for the backend server)
*   Node.js & npm (for the frontend client)

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/monopoly-local.git](https://github.com/your-username/monopoly-local.git)
   cd monopoly-local

   cd server
   go run cmd/main.go

   cd client
   npm install
   npm start