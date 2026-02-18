# BlendedSkill — Project-Verified Professional Education

A complete, production-grade LMS website built for GitHub Pages hosting.

## 🚀 Live Site

After deploying: `https://[your-github-username].github.io/Blendedskill/`

---

## 📁 File Structure

```
blendedskill/
├── index.html          ← Homepage (Hero, Courses, Tracks, Pricing, Testimonials, Contact)
├── courses.html        ← Full 12-course catalog with live search + filters
├── about.html          ← Company story, mission, timeline, values
├── privacy.html        ← Privacy Policy (placeholder — fill in your details)
├── terms.html          ← Terms of Use (placeholder)
├── accessibility.html  ← Accessibility statement (placeholder)
├── sitemap.html        ← Site map
├── css/
│   └── style.css       ← Complete design system (all pages)
├── js/
│   └── main.js         ← Navigation, animations, search, counters
└── README.md           ← This file
```

---

## 🌐 How to Deploy to GitHub Pages

### Option A — Upload via GitHub.com (Beginner)

1. Go to your repository on GitHub: `github.com/[your-username]/Blendedskill`
2. Click **"Add file"** → **"Upload files"**
3. Drag ALL files from this folder into the upload box (including the `css/` and `js/` folders)
4. Scroll down and click **"Commit changes"**
5. Go to **Settings** → **Pages** → **Source: Deploy from a branch** → **Branch: main** → **/ (root)**
6. Click **Save** — your site will be live within ~60 seconds

### Option B — Git command line

```bash
# Clone your repo
git clone https://github.com/[your-username]/Blendedskill.git
cd Blendedskill

# Copy all website files into the repo folder
# Then commit and push
git add .
git commit -m "New website: BlendedSkill 2026 redesign"
git push origin main
```

---

## ✏️ How to Update Content

### Add a new course
Open `courses.html` and copy one of the existing `<article class="course-card" ...>` blocks.
Change the `data-category` attribute to one of: `ai`, `operations`, `finance`, `data`, `cloud`

### Update pricing
Open `index.html` → find the `<!-- PRICING -->` section → edit the `.pricing-price` values.

### Change the email address
Search for `blendedskill@gmail.com` in all HTML files and replace with your email.

### Update statistics (learner count, rating, etc.)
In `index.html`, find elements with `data-counter="18000"` and change the number.

### Add a new testimonial
In `index.html`, find the `<!-- TESTIMONIALS -->` section and copy one `<blockquote class="testimonial-card">` block.

---

## 🎨 Design System

Colors (edit in `css/style.css` under `:root`):
- `--teal: #00D4B1` — Primary accent
- `--amber: #F5A623` — Secondary accent  
- `--bg-primary: #070C18` — Main background
- `--bg-secondary: #0D1528` — Section backgrounds

Fonts: **Fraunces** (headings) + **Plus Jakarta Sans** (body) — loaded from Google Fonts

---

## 📋 Pages Included

| Page | File | Status |
|------|------|--------|
| Homepage | `index.html` | ✅ Complete |
| Course Catalog | `courses.html` | ✅ Complete (12 courses) |
| About | `about.html` | ✅ Complete |
| Privacy Policy | `privacy.html` | ⚠️ Placeholder — fill in |
| Terms of Use | `terms.html` | ⚠️ Placeholder — fill in |
| Accessibility | `accessibility.html` | ⚠️ Placeholder — fill in |
| Sitemap | `sitemap.html` | ✅ Complete |

---

## 📧 Contact

To receive messages from the contact form, integrate with a service like:
- [Formspree.io](https://formspree.io) — free, easy, no backend needed
- [EmailJS](https://www.emailjs.com) — free tier available

Replace the `<form id="contact-form">` `action` attribute with your Formspree endpoint.

---

## 🛡️ Courses (2026 Catalog)

| Course | Category | Price | Duration |
|--------|----------|-------|----------|
| AI Prompt Engineering & LLM Operations | AI | $650 | 30 hrs |
| Agentic AI Workflows with Make & n8n | AI | $700 | 35 hrs |
| Generative AI for Business Leaders | AI | $450 | 24 hrs |
| Process Improvement Essentials | Operations | $500 | 40 hrs |
| Operations Automation Fundamentals | Operations | $600 | 35 hrs |
| Product Operations Management | Operations | $630 | 36 hrs |
| Payments & Financial Operations | Finance | $550 | 30 hrs |
| Risk & Controls Fundamentals | Finance | $580 | 30 hrs |
| SQL for Business Analysts | Data | $480 | 28 hrs |
| Data Analytics with Python & Pandas | Data | $620 | 40 hrs |
| Cloud Operations for Non-Engineers | Cloud | $520 | 32 hrs |
| Cybersecurity Foundations for Operations | Cloud | $490 | 28 hrs |

---

*Built for GitHub Pages — no server, no database, no build step required.*
