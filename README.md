# 📚 Engineering Library System (EduLibrary)

A modern, single-page web application designed to give B.Tech students **instant access to curated textbooks** across all subjects.
Users can search, preview, download, and organize books—all without leaving the platform.

---

## 🚀 Overview

**EduLibrary** provides a seamless digital library experience by combining:

* 📖 Subject-wise organization
* 🔍 Real-time search
* 📄 In-browser PDF reading
* ❤️ Personalized collections (Favorites & Reading List)

Everything is designed for **speed, simplicity, and student productivity**.

---

## ✨ Key Features

### 📌 1. Unified Subject Grid

* All engineering subjects displayed in a **single responsive grid**
* Each card includes:

  * Subject title
  * Short description
  * Number of available books

---

### 🔍 2. Smart Search

* Live filtering across:

  * Subjects
  * Book titles
  * Authors
* Works instantly without page reload

---

### 📚 3. Subject-Based Book View

* Click any subject to:

  * View all books
  * See cover, author, edition, rating
* Clean card-based layout

---

### 📖 4. Built-in PDF Reader

* Open books directly inside the app
* Features:

  * Modal-based viewer
  * No forced downloads
  * Smooth reading experience

---

### ⬇️ 5. Download & Open Options

* Open PDF in a new tab
* Download directly
* Supports external and hosted PDF links

---

### ❤️ 6. Favorites System

* Save important books
* Quick access anytime
* Stored using `localStorage`

---

### 📘 7. Reading List

* Build your semester study plan
* Add/remove books easily
* Persistent across sessions

---

### 🌗 8. Dark Mode

* Toggle between light and dark themes
* Smooth UI transitions
* Stored in browser memory

---

### 📊 9. Animated Statistics Section

* Displays platform metrics like:

  * Students onboarded
  * Subjects available
  * Textbooks curated

---

### 📝 10. Review System

* Users can submit feedback
* Instant UI response + toast notification

---

### 📱 11. Fully Responsive Design

* Optimized for:

  * Mobile 📱
  * Tablet 📲
  * Desktop 💻
* Smooth animations and transitions

---

## 🗂️ Project Structure

```
kotramanojkumar-edulibrary/
│
├── index.html              # Main application UI
├── README.md              # Project documentation
│
├── css/
│   └── styles.css         # Styling (responsive + themes)
│
├── js/
│   ├── script.js          # Core logic (state + UI handling)
│   ├── app.js             # Component loader (optional modular version)
│
│   ├── components/        # Modular HTML components
│   │   ├── header.html
│   │   ├── hero.html
│   │   ├── mainContent.html
│   │   ├── readerModal.html
│   │   └── footer.html
│
│   └── *.html             # Duplicate standalone component files
│
└── data/
    └── books.json         # Subjects + books dataset
```

---

## 📦 Data Source

* `books.json` contains:

  * 20+ engineering subjects
  * 4–5 books per subject
* Each book includes:

  * Title
  * Author
  * Edition
  * Rating
  * Cover image
  * PDF link

---

## ⚙️ How to Run Locally

Since the app uses `fetch()` to load JSON data, it must be served over HTTP.

---

###  VS Code Live Server

1. Open project folder in VS Code
2. Install **Live Server extension**
3. Right-click `index.html` → **Open with Live Server**



## 🧠 Core Concepts Used

* Vanilla JavaScript (No frameworks)
* DOM Manipulation
* Local Storage (state persistence)
* Event-driven architecture
* Responsive CSS (Flexbox + Grid)
* Modal UI design
* Dynamic rendering

---

## 🎯 Design Philosophy

* **Single-page experience** → no navigation friction
* **Student-first UX** → fast, minimal, distraction-free
* **Modern UI** → inspired by dashboards, not traditional libraries
* **Performance-focused** → lightweight and responsive

---

## ⚠️ Important Notes

* No backend required (fully frontend-based)
* Data is static via JSON
* PDF viewer uses embedded iframe
* Favorites & Reading List stored locally (browser)

---

## 🔮 Future Enhancements

* 🔐 User authentication (login/signup)
* ☁️ Cloud sync for reading lists
* ⭐ Book ratings & reviews system
* 📊 AI-based recommendations
* 📥 Upload your own notes/books
* 🔎 Advanced filters (year, difficulty, author)

---

## 👨‍💻 Author

**Manoj Kumar**
Engineering Library System – 2026



* Make a **GitHub-optimized version (with badges, preview GIF, screenshots)**
* Or create a **super short README for submission (1-page)**
