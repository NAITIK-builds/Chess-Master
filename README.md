# ♟️ Chess Master – Professional Chess Game

Play chess in your browser with a beautiful, modern interface, full offline support, and a powerful AI opponent.  
**Chess Master** is a professional-grade chess platform built with React, featuring local and AI play, move history, theming, sound effects, and more.

---

## ✨ Features

- **Modern, Responsive UI**: Clean, elegant design with light and dark themes.
- **Play Modes**:
  - **Local**: Play against another person on the same device.
  - **AI Opponent**: Challenge a computer with 5 difficulty levels.
- **Move History**: Scrollable, visually rich move list with turn numbers.
- **Game Status**: Real-time display of whose turn it is, move count, and game result (checkmate, stalemate, draw).
- **Player Info**: See player type (human or AI), active turn, and stats.
- **Controls**:
  - Undo/Redo moves
  - Start a new game
  - Toggle sound, theme, and game mode
  - Adjust AI difficulty on the fly
- **Offline Support**: Works fully offline; game state and settings are saved in your browser.
- **Sound Effects**: Optional move and capture sounds for an immersive experience.
- **Mobile Friendly**: Responsive board and controls for all devices.

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

```bash
git clone https://github.com/your-username/offline-chess-app.git
cd offline-chess-app
npm install
```

### Running Locally

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Building for Production

```bash
npm run build
```

---

## 🖥️ Screenshots

<!-- If you add screenshots to your repo, place them here! -->
<!-- ![Chess Master Screenshot](./screenshots/main.png) -->

---

## ⚙️ Tech Stack

- **React** (with hooks)
- **TypeScript**
- **Vite** (for fast dev/build)
- **Tailwind CSS** (utility-first styling)
- **chess.js** (game logic)
- **react-chessboard** (interactive board)
- **lucide-react** (icons)

---

## 🧩 Project Structure

```
src/
  components/      # UI components (board, controls, status, etc.)
  hooks/           # Custom React hooks (game logic, local storage)
  types/           # TypeScript types for chess state and moves
  utils/           # Utility functions (e.g., sound effects)
  index.css        # Tailwind and global styles
  main.tsx         # App entry point
```

---

## 📝 Customization

- **Themes**: Switch between light and dark mode in the controls panel.
- **AI Difficulty**: Choose from 5 levels, from beginner to expert.
- **Sound**: Toggle move/capture sounds on or off.
- **Game Mode**: Instantly switch between local and AI play.

---

## 🙏 Credits

- [chess.js](https://github.com/jhlywa/chess.js) for robust chess logic
- [react-chessboard](https://github.com/Clariity/react-chessboard) for the interactive board
- [lucide-react](https://lucide.dev/) for beautiful icons

---

## 📄 License

This project is licensed under the MIT License. 