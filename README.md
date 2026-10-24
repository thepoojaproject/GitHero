# 🐙 GitHub Clone — Interactive UI

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Pure_Frontend-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="Pure Frontend" />
</p>

<p align="center">
  <strong>A pixel-inspired, fully interactive GitHub experience — built with a single HTML file.</strong>
</p>

<p align="center">
  Create repos · Add HTML · <b>▶ Run</b> live · Star · Fork · Issues · Profile with contribution graph
</p>

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🏠 **Repo home** | Dark theme, tabs, file browser, README — GitHub-style layout |
| ➕ **New repository** | Modal flow with public/private visibility & optional README |
| 📄 **Create / edit files** | Add any file; HTML gets special treatment |
| ▶ **Run HTML** | Green **Run** on `.html` files → full-screen live preview |
| 👁 **Preview tab** | In-file Code + Preview for HTML |
| ⭐ **Star / Watch / Fork** | Toggle actions with live counters |
| 🐛 **Issues** | List + create new issues |
| 👤 **Profile** | Avatar, bio, stats, **contribution graph**, pinned repos, activity |
| ✏️ **Edit profile** | Name, bio, location, website, company — saves instantly |
| 📂 **Repos list** | Browse all your repos from logo or profile |

---

## 🚀 Quick start

1. Open **`github-clone.html`** in any modern browser  
2. No build step · No server · No dependencies  

```bash
# Optional: serve locally
npx serve .
# or
python -m http.server 8080
```

Then open the URL shown in the terminal.

---

## 🎮 How to use

### Profile
- Click the **avatar** → **Your profile**
- See the **contribution calendar**, pinned repos, and activity
- **Edit profile** to change name, bio, location, and more

### Create a repository
1. Header **+** → **New repository** (or **New** on the repos list)
2. Name it, set visibility, optional README
3. **Create repository**

### Add & run HTML
1. Inside a repo → **Add file** → **Create new file**
2. Name it e.g. `demo.html`
3. Paste your HTML → **Commit new file**
4. Click green **▶ Run** on the file row  
   — or open the file → **▶ Run** / **Preview**

Buttons, CSS, and JavaScript inside your HTML run live in the preview.

### Social actions
- **Star**, **Watch**, **Fork** on any repo  
- Counts update immediately

---

## 🛠 Tech stack

```
┌─────────────────────────────────────┐
│  github-clone.html                  │
│  ├── Semantic HTML5                 │
│  ├── CSS variables (GitHub dark)    │
│  └── Vanilla JavaScript (no libs)   │
└─────────────────────────────────────┘
```

- **Zero dependencies** — everything in one file  
- **Client-side only** — data lives in memory for the session  
- **Responsive** — works on desktop and smaller screens  

---

## 📁 Project structure

```
artifacts/
├── github-clone.html   # Full interactive app
└── README.md           # You are here
```

---

## 🎨 Design notes

- Colors aligned with GitHub dark mode (`#0d1117`, `#161b22`, `#238636`, …)
- Contribution cells use the familiar green intensity scale  
- Toasts, modals, and dropdowns mirror product UI patterns  
- HTML **Run** uses a sandboxed iframe (`allow-scripts`) for safe live demos  

---

## 👤 Default user

| Field | Value |
|-------|--------|
| **Name** | Bhim Mondal |
| **Username** | `bhim-mondal` |
| **Initials** | BM |

Change these anytime via **Edit profile** on the profile page.

---

## 📸 What you can explore

- [x] Repository code view + README  
- [x] Issues tab + new issue form  
- [x] Pull requests / Actions / Wiki placeholders  
- [x] Full-screen HTML runner with reload & new tab  
- [x] Profile overview with yearly contribution graph  
- [x] Multi-repo switching from the repos grid  

---

## ⚠️ Disclaimer

This is a **UI/UX demo**, not affiliated with GitHub, Inc.  
It does not connect to the real GitHub API. All data is local to the browser session.

---

## 📄 License

MIT — use it, fork it, learn from it.

---

<p align="center">
  Made with ☕ for learning · Open <code>github-clone.html</code> and explore
</p>
