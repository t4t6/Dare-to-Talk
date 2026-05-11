# 🦁 Dare to Talk — Website

> **"Courage is all that matters."** | সাহসই সব।

A bold, bilingual (English & Bengali) lifestyle blog/magazine website.

---

## 📁 Project Structure

```
dare-to-talk/
├── index.html              ← Homepage
├── css/
│   └── style.css           ← All styles
├── js/
│   └── main.js             ← All JavaScript
└── pages/
    ├── about.html
    ├── blog.html
    ├── services.html
    ├── pricing.html
    ├── portfolio.html
    ├── team.html
    └── contact.html
```

---

## 🚀 How to Publish on GitHub Pages (Free Hosting)

### Step 1 — Create a GitHub Account
Go to https://github.com and sign up (free).

### Step 2 — Create a New Repository
1. Click the **+** button → **New repository**
2. Name it: `dare-to-talk` (or `your-username.github.io` for a root domain)
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload Your Files
**Option A — Drag & Drop (easiest):**
1. Open your repository on GitHub
2. Click **uploading an existing file**
3. Drag the entire `dare-to-talk` folder contents
4. Click **Commit changes**

**Option B — Git (recommended):**
```bash
cd dare-to-talk
git init
git add .
git commit -m "Initial commit — Dare to Talk website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/dare-to-talk.git
git push -u origin main
```

### Step 4 — Enable GitHub Pages
1. Go to your repository → **Settings**
2. Scroll to **Pages** in the left sidebar
3. Under **Source**, select `main` branch → `/ (root)`
4. Click **Save**
5. Wait 1–2 minutes

### Step 5 — Your site is live! 🎉
URL: `https://YOUR_USERNAME.github.io/dare-to-talk/`

---

## ✏️ How to Customize Content

### Change Text
Open any `.html` file in a text editor (Notepad, VS Code, etc.) and find the text you want to change.

### Change Colors
Open `css/style.css` — all colors are in the `:root` section at the top:
```css
:root {
  --blue-deep:   #0a1f44;   /* Dark navy */
  --blue-bright: #1e88e5;   /* Main blue */
  --gold:        #f5a623;   /* Accent gold */
}
```

### Add a Blog Post
Copy any `<article class="blog-card">` block in `pages/blog.html` and change the title, date, and description.

### Add Your Logo Image
Replace the text logo in the navbar with:
```html
<img src="../images/logo.png" alt="Dare to Talk" height="40"/>
```
Then put your logo file in an `images/` folder.

### Update Pricing in BDT
Open `pages/pricing.html` and change the `৳500` and `৳2,000` values.

---

## 🌐 Custom Domain (Optional)
1. Buy a domain (e.g. from Namecheap, Google Domains)
2. In GitHub Pages settings, add your **Custom domain**
3. Update your domain DNS to point to GitHub Pages
4. Full guide: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

---

## 📧 Contact Form
The contact form currently shows a success message on submit (no backend needed).
To receive real emails, replace the form with a free service like:
- **Formspree**: https://formspree.io — add `action="https://formspree.io/f/YOUR_ID"` to the form tag
- **Web3Forms**: https://web3forms.com

---

## 🛠️ Technologies Used
- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, Animations)
- Vanilla JavaScript
- Google Fonts (Playfair Display, Barlow, Noto Sans Bengali)

No frameworks. No build tools. Just open and go. ✅

---

## 📄 License
© 2025 Dare to Talk. All rights reserved.
