# Sachin P V — Portfolio

Personal portfolio website for Sachin P V — Electronics & Instrumentation Engineering student specializing in Embedded Systems, IoT, and AI-Integrated Hardware.

## 🔗 Live Site

After deploying, your site will be available at:
```
https://<your-github-username>.github.io/sachin-portfolio/
```

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and log in
2. Click **New repository** (+ icon, top right)
3. Name it: `sachin-portfolio`
4. Set visibility to **Public**
5. Do **not** check "Initialize with README"
6. Click **Create repository**

### Step 2 — Upload files

**Option A — Drag & Drop (easiest):**
1. Open your new repo on GitHub
2. Click **uploading an existing file**
3. Drag both `index.html` and `README.md` into the upload area
4. Click **Commit changes**

**Option B — Via Git (command line):**
```bash
git init
git add .
git commit -m "Initial portfolio deploy"
git branch -M main
git remote add origin https://github.com/<your-username>/sachin-portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select `Deploy from a branch`
3. Choose branch: `main` | folder: `/ (root)`
4. Click **Save**
5. Wait ~60 seconds, then visit your live URL ✅

---

## 📁 Project Structure

```
sachin-portfolio/
├── index.html      # Main portfolio page (all-in-one)
└── README.md       # This file
```

---

## ✏️ How to Update

Edit `index.html` directly on GitHub:
1. Click `index.html` in your repo
2. Click the **pencil icon** (Edit)
3. Make your changes
4. Click **Commit changes**

Your site updates automatically within ~30 seconds.

---

## 🛠 Tech Stack

- Pure HTML, CSS, JavaScript — zero dependencies, zero build step
- Google Fonts (DM Serif Display, DM Mono, Syne)
- Intersection Observer API for scroll animations

---

*Built with Claude — Anthropic*
