# 📚 Study Buddy

An AI-powered study companion that turns your raw notes into summaries, quizzes, and flashcards — right in the browser.

**Made by Hania Batool**

## ✨ Features

- **Summarize** – Paste your notes and get a clear, bullet-point summary.
- **Quiz Mode** – Auto-generates 5 multiple-choice questions from your notes to test yourself.
- **Flashcards** – Key terms and concepts turned into flip-cards (with a smooth 3D flip animation).
- **File Upload** – Upload a `.txt` or `.md` file instead of pasting text.
- **Auto-save** – Your notes are saved locally in the browser, so they're there when you come back.
- **Animated UI** – Gradient title, floating background blobs, glowing buttons, and a splash loading screen on open.

## 🛠️ Tech Stack

- Plain HTML, CSS, and vanilla JavaScript — no build step, no dependencies.
- AI features powered by Claude.

## 🚀 Usage

Just open `index.html` in a browser. Paste notes (or upload a file), then pick **Summarize**, **Generate Quiz**, or **Flashcards**.

> Note: the AI features (`Summarize`, `Generate Quiz`, `Flashcards`) rely on a Claude-powered runtime and are designed to run inside a Claude artifact. Opening the raw HTML file outside that environment will disable those buttons, but the UI, file upload, and animations will still work.

## 📁 Project Structure

```
study-buddy/
├── index.html      # the entire app (HTML + CSS + JS)
└── README.md
```

## 📝 License

Free to use and modify.
