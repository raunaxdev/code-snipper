# Snippet Vault Workstation

A secure, web-based code snippet manager designed to store, organize, and encrypt code blocks in real time.

---

## Features

* **Google Authentication:** Integrated with Firebase Auth for seamless login.
* **Realtime Synchronization:** Automatic saving and fetching using Firebase Realtime Database.
* **Security Controls:**
  * **Domain Restrictions:** HTTP referrer rules applied to limit API key usage to authorized domains and localhost.
  * **Database Rules:** Granular access rules ensuring users can only read and write their own data.
* **Developer Workspace:** Built-in code viewer and editor interface with syntax highlights.

---

## Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Backend Services:** Firebase Realtime Database, Firebase Authentication
* **Cloud Infrastructure:** Google Cloud Platform (APIs & Credentials)
* **Hosting:** GitHub Pages / Localhost (`http://localhost:5500/`)

---

## Setup & Security Configuration

### 1. Repository Setup
```bash
git clone <repository-url>
cd code-snipper
