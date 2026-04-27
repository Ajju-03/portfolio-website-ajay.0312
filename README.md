# Ajay Kumar — ML Engineer Portfolio

A personal portfolio and resume website for **G Ajay Kumar**, Machine Learning Engineer based in Hyderabad, IN.

## 📁 Project Structure

```
portfolio/
├── index.html       ← Main HTML (structure & content)
├── style.css        ← All styles & responsive design
├── main.js          ← Interactions: cursor, scroll reveal, animations
├── assets/
│   └── ajaymachinelearning.pdf   ← Your resume PDF (add this!)
└── README.md
```

## 🚀 Deploy on GitHub Pages (Step-by-Step)

1. **Create a new GitHub repository**
   - Go to [github.com](https://github.com) → Click **New repository**
   - Name it: `your-username.github.io` (e.g. `Ajju-03.github.io`)
   - Set it to **Public**
   - Click **Create repository**

2. **Upload your files**
   - Click **Add file → Upload files**
   - Upload `index.html`, `style.css`, `main.js`
   - Create an `assets/` folder and upload your resume PDF inside it
   - Commit the changes

3. **Enable GitHub Pages**
   - Go to your repo → **Settings** → **Pages** (left sidebar)
   - Under **Source**, select `main` branch and `/ (root)` folder
   - Click **Save**

4. **Your site is live!**
   - Visit: `https://your-username.github.io`
   - It may take 1–2 minutes to go live after first deploy

## ✏️ How to Update Content

- **Personal info / text**: Edit `index.html`
- **Colors / fonts / layout**: Edit `style.css`
- **Animations / interactions**: Edit `main.js`
- **Resume PDF**: Replace `assets/ajaymachinelearning.pdf`

## 📧 Email Fix

The original site used Cloudflare's email obfuscation. The email in `index.html` has been restored to a plain `mailto:` link. Update it with your actual email address if needed:

```html
<a href="mailto:your@email.com">your@email.com</a>
```

## 🛠 Tech Stack

- HTML5 · CSS3 (Custom Properties, Grid, Flexbox)
- Vanilla JavaScript (IntersectionObserver, requestAnimationFrame)
- Google Fonts: DM Serif Display · DM Sans · DM Mono
