
# 🌊 SyncFlow Hub — Multilingual Waterfall Project & Task Engine

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-2dd4bf?style=for-the-badge)

**SyncFlow Hub** is a lightweight, responsive, single-file project management board designed for cross-border remote teams and international freelancers. It combines an animated deep-blue waterfall glassmorphism aesthetic with instant multi-language switching, customizable topic boards, and persistent Kanban task management.

---

## ✨ Key Features

* **🌐 Instant Multilingual Interface (i18n):** Switch seamlessly between **English (EN)**, **German (DE)**, **Nepali (NE)**, **Spanish (ES)**, **French (FR)**, **Hindi (HI)**, **Japanese (JA)**, **Korean (KO)**, **Arabic (AR)**, **Chinese (ZH)**, or enter any custom ISO language code without reloading the page.
* **🗂️ Dynamic Topic & Subtopic Architecture:** Create custom project workspaces (Topics) and filterable tags (Subtopics) on the fly to organize multiple workflows inside one hub.
* **📋 Interactive Kanban Board:**
  * **Desktop Drag-and-Drop:** Smoothly drag task cards across **To Do**, **In Progress**, and **Completed** columns with visual dropzone highlights.
  * **Mobile Quick-Move Controls:** Built-in directional stage buttons (`◀` / `▶`) on every card for effortless touch interaction on mobile devices.
* **💾 Automatic LocalStorage Persistence:** All custom topics, subtopics, language preferences, and task states save automatically in the browser, with a one-click **Reset Demo** option.
* **💧 Immersive Waterfall UI & Tactile Feedback:** Features a layered CSS waterfall animation, pulsing foam/mist effects, 45 falling droplet particles, frosted glass panels (`backdrop-filter`), and pointer-origin water-ripple animations on every click.

---

## 🚀 Quick Start & Local Usage

Because **SyncFlow Hub** is built with zero external build tools or frameworks, you can run it anywhere in seconds:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   cd YOUR-REPO-NAME
   ```
2. **Open in your browser:**
   * Double-click `index.html` (or `bilingual-task-hub.html`) to open it directly in any modern browser.
   * Or serve it locally via Python:
     ```bash
     python3 -m http.server 8080
     ```
     Then visit `http://localhost:8080`.

---

## 🌍 Deploying Live on GitHub Pages

1. Push `index.html` and `README.md` to your GitHub repository's `main` branch.
2. Go to **Settings** → **Pages** in your repository.
3. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
4. Your live interactive portfolio demo will be published at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`.

---

## 🛠️ Tech Stack

* **Structure:** Semantic HTML5
* **Styling:** Custom CSS3 Variables, Flexbox/Grid, Glassmorphism (`backdrop-filter`), Keyframe Animations
* **Logic & State:** Vanilla ES6+ JavaScript, HTML5 Drag & Drop API, Web Storage API (`localStorage`)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
