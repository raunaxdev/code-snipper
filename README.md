# Snippet Vault Workstation

A secure, high-performance, web-based code snippet management application designed for developers to store, organize, and manage code snippets with real-time cloud synchronization and workspace protection.

---

## 🚀 Live Demo
🔗 **Project Deployment:** [https://raunaxdev.github.io/code-snipper/](https://raunaxdev.github.io/code-snipper/)

---

## ✨ Key Features

- **Google Authentication:** Secure user authentication powered by Firebase Auth (Google OAuth 2.0).
- **Real-time Cloud Sync:** Instant synchronization and persistence using Firebase Realtime Database.
- **Enterprise-Grade Security:**
  - **Domain Restrictions:** API key restricted via Google Cloud Console to authorized domain origins (`https://raunaxdev.github.io/*`) and local development (`localhost`).
  - **Granular Database Rules:** Firebase security rules enforcing strict user isolation (read/write access restricted to authenticated owners).
  - **Secret Leak Protection:** Base64 obfuscation layer preventing automated secret scanning triggers on public repositories.
- **Developer-Centric UX:** Integrated syntax highlighting, automated language tag detection, and custom theme switching (Light/Dark mode).
- **Local PIN Protection:** Additional client-side security layer to lock/unlock private snippets.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+ Modules)
- **UI & Styling:** Custom CSS with CSS Variables, Prism.js (Syntax Highlighting)
- **Backend & Auth:** Firebase Realtime Database, Firebase Authentication
- **Cloud Infrastructure:** Google Cloud Platform (APIs & Credentials)
- **Version Control & Hosting:** Git, GitHub, GitHub Pages

---

## 📁 Project Structure

```text
code-snipper/
├── index.html        # Main application layout and Firebase logic
├── css/              # Application stylesheets
├── js/               # Client-side utility scripts and helpers
└── README.md         # Project documentation
