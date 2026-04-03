
  <h1>BYI VIBE CODER — Bring Any Idea to Life</h1>

  <p>Upload an image of a board game, floor layout, sketch, or anything you can imagine — and watch it transform into a fully interactive web experience, powered by Google Gemini AI.</p>

  <p>
    <img alt="React" src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white&style=flat-square" />
    <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript&logoColor=white&style=flat-square" />
    <img alt="Vite" src="https://img.shields.io/badge/Vite-6-646CFF?logo=vite&logoColor=white&style=flat-square" />
    <img alt="Gemini" src="https://img.shields.io/badge/Google%20Gemini%20AI-powered-4285F4?logo=google&logoColor=white&style=flat-square" />
    <img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-green?style=flat-square" />
  </p>
</div>

---

## ✨ Features

- 🖼️ **Image-to-Experience** — Upload any image and let Gemini AI turn it into a live, interactive HTML app
- 🎮 **Works with anything** — Board games, floor plans, sketches, diagrams, cassette tapes, and more
- 🕒 **Creation History** — All your generations are saved locally so you can revisit them anytime
- 📤 **Import & Export** — Share your creations as JSON artifacts or import them from others
- ⚡ **Blazing fast** — Built with Vite + React 19 for a snappy developer and user experience
- 🌙 **Dark UI** — Sleek dark theme with a dot-grid background

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- A [Google Gemini API key](https://aistudio.google.com/app/apikey)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/utkarsh232005/BYI-VIBE-CODER.git
   cd BYI-VIBE-CODER
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up your API key:**
   ```bash
   cp .env.example .env.local
   ```
   Then open `.env.local` and replace the placeholder with your actual key:
   ```env
   VITE_GOOGLE_API_KEY=your_actual_api_key_here
   ```
   > Get your free API key from [Google AI Studio](https://aistudio.google.com/app/apikey)

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. Open your browser at the URL shown (usually `http://localhost:3000` or `http://localhost:3001`).

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| [React 19](https://react.dev/) | UI framework |
| [TypeScript 5.8](https://www.typescriptlang.org/) | Type-safe JavaScript |
| [Vite 6](https://vitejs.dev/) | Build tool & dev server |
| [Google Gemini AI (`@google/genai`)](https://ai.google.dev/) | AI image-to-HTML generation |
| [Heroicons](https://heroicons.com/) | Icon library |

---

## 📁 Project Structure

```
BYI-VIBE-CODER/
├── components/
│   ├── Hero.tsx           # Landing page hero section
│   ├── InputArea.tsx      # Prompt & file upload input
│   ├── LivePreview.tsx    # Fullscreen HTML preview pane
│   └── CreationHistory.tsx # Sidebar of past creations
├── services/
│   └── gemini.ts          # Gemini AI integration
├── App.tsx                # Root application component
├── index.tsx              # Entry point
├── index.html             # HTML shell
├── .env.example           # Environment variable template
└── vite.config.ts         # Vite configuration
```

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build locally |

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open an [issue](https://github.com/utkarsh232005/BYI-VIBE-CODER/issues) or submit a pull request.

---

## 👤 Author

**Utkarsh Patrikar**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-utkarsh--patrikar-0A66C2?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/utkarsh-patrikar/)

---

## 📄 License

This project is licensed under the [Apache 2.0 License](LICENSE).

