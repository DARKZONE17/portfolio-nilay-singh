# 🚀 Nilay Singh — Personal Portfolio Website

A clean, modern, dark-themed personal portfolio website for **Nilay Singh**, a Data Engineer specializing in Azure, Databricks, and Apache Spark.

---

## 📸 Preview

> A fully responsive, single-page portfolio with smooth scroll navigation, animated sections, and a professional dark aesthetic.

---

## 📁 Project Structure

```
portfolio/
├── index.html                  # Main portfolio website
└── Nilay_Singh_Resume.docx     # Resume file (linked for download)
```

---

## ✨ Features

- **Responsive Design** — Works seamlessly on desktop, tablet, and mobile
- **Fixed Navigation** — Smooth scroll to all sections with a glassmorphism navbar
- **Hero Section** — Intro with name, title, and call-to-action buttons
- **About / Stats** — Key impact numbers pulled from real project experience
- **Education** — B.Tech from DIT University with relevant coursework
- **Work Experience** — Visual timeline of roles at Celebal Technologies
- **Projects** — 3 featured data engineering projects with performance metrics
- **Skills** — Categorized tech stack with color-coded pill tags
- **Certifications** — 6 Microsoft & Databricks credentials
- **Resume Section** — One-click resume download with quick-glance info cards
- **Contact** — Email and LinkedIn with availability status

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure and semantic markup |
| CSS3 | Custom properties, Grid, Flexbox, animations |
| Vanilla JavaScript | Smooth interactions (no frameworks needed) |

No build tools, no dependencies, no npm — just open the file and it works.

---

## 🚀 Deployment

### Option 1 — Netlify (Recommended, ~2 minutes)

1. Go to [netlify.com](https://netlify.com) and sign up for free
2. Drag and drop the `portfolio/` folder onto the Netlify dashboard
3. Your site is live at `https://your-name.netlify.app`
4. Optionally customize the subdomain under **Site Settings → Domain**

### Option 2 — GitHub Pages

1. Create a new GitHub repository named `your-username.github.io`
2. Rename `index.html` if not already done, then upload both files
3. Go to **Settings → Pages → Deploy from branch → main**
4. Live at `https://your-username.github.io`

### Option 3 — Vercel

1. Push the folder to a GitHub repo
2. Import the repo at [vercel.com](https://vercel.com)
3. Vercel auto-deploys on every push

> **Important:** Keep `index.html` and `Nilay_Singh_Resume.docx` in the **same directory** so the resume download button works correctly.

---

## 🎨 Customization

### Update Personal Info

Open `index.html` and search for the following to update:

| What to change | Search for |
|----------------|------------|
| Email address | `nilaysingh.work@gmail.com` |
| LinkedIn URL | `linkedin.com/in/nilay-singh` |
| Resume file | `Nilay_Singh_Resume.docx` |
| Hero badge text | `Available for Opportunities` |

### Update Colors

All colors are defined as CSS variables at the top of the `<style>` block:

```css
:root {
  --bg: #0a0e1a;         /* Page background */
  --card: #141c2e;       /* Card background */
  --accent: #38bdf8;     /* Primary accent (cyan) */
  --accent2: #818cf8;    /* Secondary accent (indigo) */
  --accent3: #34d399;    /* Tertiary accent (emerald) */
  --text: #e2e8f0;       /* Primary text */
  --muted: #94a3b8;      /* Muted text */
}
```

### Add a New Section

1. Add a nav link: `<li><a href="#new-section">New</a></li>`
2. Add a divider: `<hr class="divider">`
3. Add the section:
```html
<section id="new-section">
  <div class="section-label">Label</div>
  <div class="section-title">Section Title</div>
  <p class="section-subtitle">Short description here.</p>
  <!-- your content -->
</section>
```

---

## 📄 License

This project is personal and not licensed for redistribution. All content, experience, and credentials belong to **Nilay Singh**.

---

## 🙋 About

**Nilay Singh** is a Data Engineer at Celebal Technologies with expertise in:

- **Cloud:** Microsoft Azure, Microsoft Fabric
- **Big Data:** Apache Spark, Databricks, Delta Lake
- **Languages:** Python, SQL, PySpark
- **Architecture:** Medallion Architecture, ETL/ELT, Data Warehousing

📧 nilaysingh.work@gmail.com  
🔗 [linkedin.com/in/nilay-singh](https://linkedin.com/in/nilay-singh)  
📍 India · Open to remote & on-site roles
