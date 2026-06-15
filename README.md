# 🌸 Tala Al-Khateeb — Frontend Training Project

> A 5-page interactive web project built as part of a web development internship, demonstrating proficiency in HTML5, CSS3, Bootstrap 5, and JavaScript.

---

## 👩‍💻 About the Developer

**Tala Al-Khateeb** — 5th-year Software Engineering student at the Syrian Private University (SPU), passionate about backend engineering, systems analysis, and artificial intelligence.

- 🐙 [GitHub](https://github.com/Talalkhateeb)
- 💼 [LinkedIn](https://www.linkedin.com/in/tala-al-khateeb-6012ba265)
- 📧 engtalaalkhateeb2004@gmail.com

---

## 🗂️ Project Structure

```
├── index.html            # Home page — about me + navigation hub
├── portfolio.html        # Page 1 — Interactive Portfolio
├── blog.html             # Page 2 — Technical Blog (34 articles)
├── Glossystore.html      # Page 3 — Glossy Store (product gallery)
├── calculator.html       # Page 4 — Functional Calculator
├── consultationform.html # Page 5 — Consultation Form with validation
└── style.css             # Global custom stylesheet
```

---

## 📄 Pages Overview

### 🏠 Home (`index.html`)

The landing page with a brief bio and navigation buttons linking to all 5 project pages.

---

### 💼 Page 1 — Portfolio (`portfolio.html`)

A two-column personal portfolio layout showcasing projects and social links.

**Features:**

- Responsive two-panel layout (sidebar + main content) using Bootstrap Grid
- Circular profile photo with custom border styling
- Project cards with links (Calculator, Glossy Store, Consultation Form, GPDetect)
- Social links: GitHub, LinkedIn, Email
- **JS Interaction:** 🌙 Dark/Light mode toggle with smooth visual transition

---

### 📝 Page 2 — Blog (`blog.html`)

A dynamically generated blog archive of 34 technical articles.

**Features:**

- All 34 article cards generated via JavaScript loop (no repetitive HTML)
- Category badges (Web Dev, AI & ML, Database, UI/UX, Cybersecurity, Software Architecture)
- Publish dates auto-generated per article
- **JS Interaction:** "Read More" button opens a Bootstrap Modal with the full article content

---

### 🛍️ Page 3 — Glossy Store (`Glossystore.html`)

A beauty & lifestyle e-commerce product gallery.

**Features:**

- 8 product cards using Bootstrap Cards with hover animation
- Category filter buttons (All, Skincare, Makeup, Fragrance, Accessories)
- Star ratings and review counts per product
- **JS Interaction (×2):**
  - 🛒 Cart counter that increments on "Add to Cart"
  - 🔍 Live category filtering that shows/hides products instantly
  - ✅ Toast notification confirming each item added

---

### 🧮 Page 4 — Calculator (`calculator.html`)

A fully functional calculator with a sleek dark display.

**Features:**

- Full arithmetic operations: `+`, `−`, `×`, `÷`, `%`, `+/−`
- Expression display showing the full operation before result
- Smart number formatting for long results
- **JS Interaction:** Complete calculator logic with operator chaining and error handling (`÷ 0 → Error`)
- ⌨️ **Bonus:** Full keyboard support (`0–9`, operators, `Enter`, `Escape`)

---

### 📋 Page 5 — Consultation Form (`consultationform.html`)

A multi-field booking form with real-time validation.

**Features:**

- Fields: Full Name, Email, Phone (optional), Topic (radio chips), Message, Privacy checkbox
- **JS Interaction (×3):**
  - ✅ Full field validation on submit (prevents empty/invalid submission)
  - 📊 3-step progress indicator that fills as you complete key fields
  - 🔢 Live character counter for the message field (max 500)
- 🎉 Success screen after valid submission with personalized confirmation
- Reset button to submit another request

---

## ✅ Requirements Checklist

| Requirement                                                     | Status |
| --------------------------------------------------------------- | ------ |
| HTML5 semantic elements (`header`, `main`, `section`, `footer`) | ✅     |
| `meta viewport` for responsiveness                              | ✅     |
| Separate external CSS file (`style.css`)                        | ✅     |
| CSS custom colors, fonts, and margins overriding Bootstrap      | ✅     |
| Bootstrap 5 Grid system                                         | ✅     |
| Bootstrap Navbar                                                | ✅     |
| Bootstrap Cards                                                 | ✅     |
| Bootstrap Forms                                                 | ✅     |
| At least 1 JavaScript interaction per page                      | ✅     |
| Fully responsive (mobile, tablet, desktop)                      | ✅     |
| `index.html` links to all 5 pages                               | ✅     |
| No console errors                                               | ✅     |

---

## 🛠️ Technologies Used

| Technology | Version | Usage                            |
| ---------- | ------- | -------------------------------- |
| HTML5      | —       | Semantic page structure          |
| CSS3       | —       | Custom styling & dark mode       |
| Bootstrap  | 5.3.8   | Grid, components, utilities      |
| JavaScript | ES6+    | Interactivity & DOM manipulation |
| Cloudinary | —       | Profile image hosting            |

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Talalkhateeb/<repo-name>.git
   ```
2. Open `index.html` in any modern browser — no build step or server required.

> All pages work offline except the profile image (hosted on Cloudinary CDN).

---

## 🌐 Live Demo

🔗 [View on GitHub Pages](#) _(https://talalkhateeb.github.io/Random-Projects-/)_

---

## 📅 Submission

**Deadline:** One week from assignment date

**Submitted by:** Tala Al-Khateeb — 15 June 2026
