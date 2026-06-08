# 🎯 AI Interview Coach

> Practice. Improve. Succeed. — Powered by Claude AI

---

## 🚀 Quick Start

### Option 1: Open Directly in Browser
1. Open `index.html` in any modern browser (Chrome, Firefox, Edge)
2. That's it — no install needed!

### Option 2: VS Code Live Server (Recommended)
1. Install the **Live Server** extension in VS Code
2. Open the project folder in VS Code
3. Right-click `index.html` → **Open with Live Server**
4. App opens at `http://127.0.0.1:5500`

---

## 🔑 Getting Your API Key

1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up / log in
3. Click **API Keys** → **Create Key**
4. Copy the key (starts with `sk-ant-`)
5. Paste it in the **Setup** page of the app

> Your key is stored in your browser's localStorage — it never leaves your machine.

---

## ✨ Features

| Feature | Description |
|---|---|
| **AI Questions** | Generates personalized interview questions using Claude AI |
| **Resume Upload** | Upload PDF or TXT resume for tailored questions |
| **Answer Evaluation** | Real-time AI scoring on 4 dimensions |
| **Feedback** | Strengths, improvements, and sample better answers |
| **Progress Dashboard** | Track scores across sessions with charts |
| **Study Plan** | AI-generated personalized improvement plan |
| **Session History** | Last 20 sessions stored locally |

---

## 📊 Evaluation Rubrics

- **Communication Clarity** — How clearly you express ideas
- **Technical Accuracy** — Depth and correctness of technical answers
- **STAR Format** — Situation → Task → Action → Result structure
- **Confidence Score** — Consistency and assertiveness of answers

---

## 🗂 Project Structure

```
ai-interview-coach/
├── index.html          ← Single page app (all 4 pages)
├── css/
│   └── style.css       ← All styles
├── js/
│   └── app.js          ← All logic, state, API calls
└── README.md
```

---

## ⚙️ Tech Stack

- **Vanilla HTML/CSS/JS** — No build tools, no dependencies to install
- **Anthropic Claude API** — `claude-sonnet-4-20250514` for all AI features
- **Chart.js** (CDN) — Dashboard charts
- **Font Awesome** (CDN) — Icons
- **Google Fonts** (CDN) — Syne + DM Sans typography

---

## 💡 Tips

- Use **Ctrl+Enter** to quickly submit an answer
- Try the **Mixed** interview type for a comprehensive practice
- Upload your actual resume for the most relevant questions
- Complete at least 3 sessions to see meaningful trend charts
- The study plan updates after each completed session

---

## 🛠 Troubleshooting

**"Error: 401 Unauthorized"** → Check your API key is correct  
**"Error: 429 Too Many Requests"** → Wait a moment and try again  
**PDF not reading correctly** → Save resume as .txt and re-upload  
**Charts not showing** → Ensure internet connection (Chart.js loads from CDN)

---

Made with ❤️ — Harshu 202
