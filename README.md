# 🎓 Jihawii Prep Challenge (French & Arabic) 🇲🇦

An interactive, premium web application designed to help Moroccan **1st Baccalaureate (1 Bac)** students prepare for their Regional Exam (**Exam Regional / Jihawii**). 

This project consists of two beautifully designed standalone challenges featuring quiz databases, interactive grammar and rhetoric revision, and advanced **AI-powered features** (such as essay correction and stress simulation) powered by Groq AI.

---

## 🚀 Features

### 🇫🇷 1. Défi Zéro Faute — French Challenge (`French_challenge.html`)
* **Interactive Spelling Quiz (Orthographe):** Covers common tricky words, past participle agreements, homophones, and vocabulary related to the 1st Bac curriculum (*Antigone*, *Le Dernier Jour d'un condamné*, *La Boîte à merveilles*).
* **Logical Connectors (Connecteurs logiques):** Practice structuring argumentative essays using correct transition words.
* **AI Correcteur Orthographique:** An AI-powered assistant that reviews, scores, and provides comprehensive feedback on French written expressions.
* **AI Stress Simulator:** A feature simulating real-life exam pressure with dynamic AI responses to test-taking anxiety.

### 🇲🇦 2. تحدي اللغة العربية — Arabic Challenge (`arabic_challenge.html`)
* **Language Science (علوم اللغة):** Interactive quizzes on grammar and morphology rules (التمييز والعدد، النسبة والمصادر).
* **Rhetorical Methods (الأساليب والظواهر البلاغية):** Exercises on commands, prohibitions, wishes, and questioning (الأمر، النهي، التمني والاستفهام).
* **Themes & Concepts (قضايا ومفاهيم النصوص):** Test comprehension of major text themes like development, technology, and human values (التنمية، التكنولوجيا، والقيم الإنسانية).
* **Expression & Synthesis (مهارات التعبير والإنشاء):** Learn the steps of expanding an idea (توسيع فكرة) and linking arguments.
* **AI Essay Grading & Correction:** Input essay prompts or answers to receive detailed grammatical and structural feedback from an AI evaluator.

---

## 🛠️ Technology Stack

* **Structure:** Vanilla HTML5 with modern semantic tags.
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (loaded via CDN) for responsive, utility-first layout styling.
* **Fonts:** 
  * `Inter` from Google Fonts for the French Challenge.
  * `Tajawal` from Google Fonts for the Arabic Challenge (with full RTL support).
* **Icons:** [Phosphor Icons](https://phosphoricons.com/) for micro-interactions and interface indicators.
* **AI Integration:** [Groq API](https://console.groq.com/) using the `llama-3.3-70b-versatile` model.

---

## 🔑 AI Setup & Privacy

Both applications feature an optional AI configuration modal:
1. Click the CPU settings icon in the interface.
2. Enter your **Groq API Key** (`gsk_...`), which you can get for free at [console.groq.com](https://console.groq.com/).
3. Click **Save / Enregistrer**.

> [!IMPORTANT]
> **Privacy First:** Your API key is stored **locally** on your computer using the browser's `localStorage`. It is never uploaded to any external server other than the official Groq API endpoint.

---

## 💻 How to Run

Since the application is built entirely as client-side standalone files, there are no build steps required:

1. Double-click either `French_challenge.html` or `arabic_challenge.html` to open it in your browser.
2. Alternatively, run them using a local development server like **Live Server** in VS Code or python:
   ```bash
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your web browser.
