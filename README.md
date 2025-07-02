# 🏆 Chess Master
### *Professional Chess Game – Play Like a Grandmaster*

<div align="center">

![Chess Master Banner](https://img.shields.io/badge/Chess-Master-gold?style=for-the-badge&logo=chess&logoColor=white)
[![React](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-4+-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3+-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

*Experience chess like never before with our modern, feature-rich chess platform*

[🚀 **Play Now**](https://chess-master-mu.vercel.app) • [📖 **Documentation**](#-features) • [🎯 **Live Demo**](https://chess-master-mu.vercel.app) • [💬 **GitHub**](https://github.com/NAITIK-builds/Chess-Master)

</div>

---

## 🌟 **Why Chess Master?**

<table>
<tr>
<td>

**🎨 Beautiful Design**
- Sleek, modern interface
- Light & dark themes
- Responsive on all devices
- Professional animations

</td>
<td>

**🤖 Smart AI Opponent**
- 5 difficulty levels
- Intelligent move analysis
- Adaptive gameplay
- Challenge progression

</td>
</tr>
<tr>
<td>

**⚡ Lightning Fast**
- Instant game loading
- Smooth interactions
- Offline capability
- Zero lag gameplay

</td>
<td>

**🎵 Immersive Experience**
- Authentic sound effects
- Move history tracking
- Game state persistence
- Professional feel

</td>
</tr>
</table>

---

## ✨ **Features**

### 🎮 **Game Modes**
- **👥 Local Play** - Challenge friends on the same device
- **🤖 AI Opponent** - Battle against 5 difficulty levels

### 🎯 **Core Features**
```
🏁 Real-time game status      📱 Mobile-optimized design
📜 Complete move history      🔊 Optional sound effects  
⚡ Undo/Redo functionality    🌓 Light & dark themes
💾 Auto-save game state      🎚️ Adjustable AI difficulty
```

### 🛠️ **Advanced Controls**
| Feature | Description |
|---------|-------------|
| **Move Validation** | Instant legal move checking with visual feedback |
| **Game Analysis** | Track moves, captures, and strategic decisions |
| **Theme Switcher** | Seamlessly toggle between light and dark modes |
| **Sound Manager** | Customize audio experience with move/capture sounds |
| **Game Reset** | Start fresh anytime with one-click reset |

---

## 🚀 **Quick Start**

### 📋 **Prerequisites**
- Node.js 16+ 
- npm or yarn package manager

### ⚡ **Installation**
```bash
# Clone the repository
git clone https://github.com/NAITIK-builds/Chess-Master.git

# Navigate to project directory  
cd Chess-Master

# Install dependencies
npm install

# Start development server
npm run dev
```

### 🌐 **Access Your Game**
Open your browser and navigate to: **http://localhost:5173**

Or visit the live demo: **[chess-master-mu.vercel.app](https://chess-master-mu.vercel.app)**

### 🏗️ **Build for Production**
```bash
npm run build
npm run preview  # Preview production build
```

---

## 🖼️ **Screenshots**

<div align="center">

### 🌅 **Light Theme**
*Clean, professional interface perfect for focused gameplay*

<img src="https://i.ibb.co/JjRd907S/chess-master-mu-vercel-app.png" alt="Chess Master Light Theme" width="700" style="border-radius: 10px; box-shadow: 0 4px 20px rgba(0,0,0,0.1); margin: 20px 0;"/>

### 🌙 **Dark Theme** 
*Elegant dark mode for comfortable extended sessions*

<img src="https://i.ibb.co/pjVsxGJL/chess-master-mu-vercel-app-1.png" alt="Chess Master Dark Theme" width="700" style="border-radius: 10px; box-shadow: 0 4px 20px rgba(0,0,0,0.3); margin: 20px 0;"/>

### ✨ **Key Visual Features**
- Beautiful chess piece designs with smooth animations
- Intuitive move history panel with algebraic notation
- Clean game controls with material design principles
- Responsive layout that adapts to any screen size

</div>

---

## 🏗️ **Architecture**

### 🧩 **Project Structure**
```
src/
├── 🧩 components/          # Reusable UI components
│   ├── Board/             # Chess board and pieces
│   ├── Controls/          # Game control panel
│   ├── History/           # Move history display
│   └── Status/            # Game status indicators
├── 🎣 hooks/              # Custom React hooks
│   ├── useChessGame.ts    # Core game logic
│   ├── useLocalStorage.ts # Data persistence
│   └── useAI.ts           # AI opponent logic
├── 🎯 types/              # TypeScript definitions
├── 🛠️ utils/              # Helper functions
└── 🎨 styles/             # Global styles & themes
```

### 🔧 **Tech Stack**
<div align="center">

| Technology | Purpose | Version |
|------------|---------|---------|
| **React** | UI Framework | 18+ |
| **TypeScript** | Type Safety | 5+ |
| **Vite** | Build Tool | 4+ |
| **Tailwind CSS** | Styling | 3+ |
| **chess.js** | Game Logic | Latest |
| **react-chessboard** | Board Component | Latest |
| **Lucide React** | Icons | Latest |

</div>

---

## ⚙️ **Configuration**

### 🎨 **Theming**
```typescript
// Customize themes in src/styles/themes.ts
export const themes = {
  light: {
    background: '#ffffff',
    primary: '#1f2937',
    secondary: '#6b7280'
  },
  dark: {
    background: '#1f2937', 
    primary: '#ffffff',
    secondary: '#9ca3af'
  }
}
```

### 🤖 **AI Settings**
```typescript
// Adjust AI difficulty in src/utils/ai.ts
export const AI_LEVELS = {
  1: { depth: 1, name: 'Beginner' },
  2: { depth: 2, name: 'Novice' },
  3: { depth: 3, name: 'Intermediate' },
  4: { depth: 4, name: 'Advanced' },
  5: { depth: 5, name: 'Expert' }
}
```

---

## 🎯 **Development**

### 🛠️ **Local Development**
```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

### 🧪 **Testing**
```bash
# Run tests
npm test

# Run tests with coverage
npm run test:coverage
```

---

## 🤝 **Contributing**

We welcome contributions! Here's how you can help:

### 🐛 **Bug Reports**
Found a bug? [Open an issue](https://github.com/NAITIK-builds/Chess-Master/issues) with:
- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if applicable

### 💻 **Code Contributions**
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### 📝 **Development Guidelines**
- Follow TypeScript best practices
- Maintain test coverage above 80%
- Use conventional commit messages
- Update documentation for new features

---

## 🙏 **Acknowledgments**

### 🏆 **Core Dependencies**
- **[chess.js](https://github.com/jhlywa/chess.js)** - Robust chess move generation and validation
- **[react-chessboard](https://github.com/Clariity/react-chessboard)** - Beautiful, interactive chess board
- **[Lucide React](https://lucide.dev/)** - Crisp, customizable icons

### 💝 **Special Thanks**
- Chess.com for inspiration on modern chess interfaces
- The React community for excellent ecosystem tools
- All contributors who help make this project better

---

<div align="center">

**⭐ Star this repo if you love Chess Master! ⭐**

[🐛 Report Bug](https://github.com/NAITIK-builds/Chess-Master/issues) • [✨ Request Feature](https://github.com/NAITIK-builds/Chess-Master/issues) • [🚀 Live Demo](https://chess-master-mu.vercel.app)

---

*Made with ❤️ by passionate chess enthusiasts*

</div>