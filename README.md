# NeuroLearn: Interactive AIML Learning Platform

NeuroLearn is a comprehensive, client-side web application designed to teach Artificial Intelligence and Machine Learning concepts through interactive modules, coding playgrounds, and AI-driven tutoring.

## 🚀 Features

- **User Authentication**: Lightweight username-based login system using `localStorage`.
- **Structured Learning**: 9 modules covering Beginner to Advanced topics (Linear Regression, Neural Networks, SVM, PCA, etc.).
- **Interactive Coding Playground**: In-browser Python environment powered by **Pyodide**.
- **Gamification**: Earn points, maintain streaks, and unlock badges (Novice, Expert, Master, Scholar).
- **AI Tutor**: Real-time doubt solver powered by **Gemini API**, providing detailed explanations and dynamic charts.
- **Mini-Games**: Concept-based games like "Fast Classifier" to reinforce learning.
- **Voice Explanations**: Integrated text-to-speech for all learning content and AI responses.
- **Leaderboard**: Compete with other local users based on scores.

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript, Vite
- **Styling**: Tailwind CSS, Lucide Icons
- **AI**: Google Gemini API (via REST)
- **Charts**: Chart.js, React-Chartjs-2
- **Python Runtime**: Pyodide
- **Persistence**: Browser LocalStorage

## 📦 Installation

1. Clone the repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up your environment variables in a `.env` file:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## 📜 License

MIT License. Built for the Vibethon Hackathon.
