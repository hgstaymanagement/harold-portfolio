# Harold Winston Guadiz — Portfolio

**Short-Term Rental Property Manager | Guesty Specialist | Airbnb Co-Host**

---

## 🚀 Deploy to Render (Step-by-Step)

### Step 1 — Push to GitHub

1. Create a new repository on [github.com](https://github.com/new)
2. Name it `harold-portfolio` (or anything you like)
3. Run these commands in your terminal inside this folder:

```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/harold-portfolio.git
git push -u origin main
```

---

### Step 2 — Deploy on Render

1. Go to [render.com](https://render.com) and sign up / log in
2. Click **"New +"** → **"Web Service"**
3. Connect your GitHub account and select the `harold-portfolio` repo
4. Fill in the settings:

| Setting | Value |
|---|---|
| **Name** | `harold-portfolio` |
| **Runtime** | `Node` |
| **Build Command** | `npm install` |
| **Start Command** | `npm start` |
| **Plan** | Free |

5. Click **"Create Web Service"**
6. Wait ~2 minutes — Render will give you a live URL like:
   `https://harold-portfolio.onrender.com`

---

### Step 3 — Update Your Contact Info

Before deploying, update these placeholders in `index.html`:

- `your@email.com` → your real email
- `linkedin.com/in/yourprofile` → your LinkedIn URL
- `facebook.com/yourpage` → your Facebook URL

---

## 📁 File Structure

```
harold-portfolio/
├── index.html      ← Main portfolio page
├── style.css       ← All styles
├── server.js       ← Express server for Render
├── package.json    ← Node dependencies
├── render.yaml     ← Render config
├── .gitignore
└── README.md
```

## 🛠 Local Preview

```bash
npm install
npm start
# Open http://localhost:3000
```
