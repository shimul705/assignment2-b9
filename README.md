# ✈️ Bengal Travel — Travel Agency Landing Page

A modern, responsive landing page for a travel agency, built with **pure HTML5 and CSS3**. It covers destination browsing, tour packages, pricing plans and a newsletter sign-up.

> **Programming Hero — Level 1 · Assignment 2 (Batch 9)**
> Completed: **January 16, 2024**

<p>
  <a href="https://shimul705.github.io/assignment2-b9/"><img alt="Live Demo" src="https://img.shields.io/badge/Live-Demo-FF5400?style=for-the-badge&logo=githubpages&logoColor=white"></a>
  <a href="https://github.com/shimul705/assignment2-b9"><img alt="Source Code" src="https://img.shields.io/badge/Source-Code-131318?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

## 🔗 Links

| | |
|---|---|
| **Live Site** | [shimul705.github.io/assignment2-b9](https://shimul705.github.io/assignment2-b9/) |
| **Repository** | [github.com/shimul705/assignment2-b9](https://github.com/shimul705/assignment2-b9) |

---

## 📌 Overview

**Bengal Travel** is my second Programming Hero assignment. It turns a travel agency design into a static web page using only semantic HTML and hand-written CSS.

Compared with Assignment 1, this project uses **CSS Grid** for a gallery with mixed card sizes, a **pricing card** layout, an embedded **YouTube video**, and **mobile touches** such as a hamburger icon and a stacked search form. It also adds two bonus sections beyond the required design: **Our Plans** and **A Simple Perfect Place To Get Lost**.

---

## ✨ Page Sections

1. **Navbar:** the logo with brand colours, the navigation links, and a hamburger icon on mobile.
2. **Hero Banner:** a background image with a gradient overlay and a search bar (Where / When / Type / Find Now).
3. **Our Popular Tours:** text and a bullet list beside a feature image.
4. **Choose Your Destination:** a 7-card gallery built with CSS Grid (2 / 3 / 2 rows) with centred titles over the images.
5. **Why Choose Us:** three feature cards (Handpicked Hotels, World Class Service, Best Price Guarantee).
6. **Our Plans (bonus):** three pricing cards with gradient backgrounds, feature lists and a "Join Now" button.
7. **A Simple Perfect Place To Get Lost (bonus):** content beside an embedded YouTube video.
8. **Newsletter:** a sign-up form beside a "Save up to 70%" offer image with a rotated badge.
9. **Footer:** the logo, a short description, social icons and copyright.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic structure (`header`, `nav`, `main`, `form`, `footer`) and an embedded `iframe` |
| **CSS3** | Flexbox, CSS Grid, absolute positioning, `transform: rotate()`, gradients, box shadows, media queries |
| **Google Fonts** | `Mulish` (400, 700, 800) and `Inter` (300) |
| **GitHub Pages** | Deployment |

---

## 📱 Responsive Design

| Breakpoint | Device | Layout |
|---|---|---|
| `> 1024px` | Desktop | Full layout: two-column sections, three pricing cards in a row, a 2/3/2 destination grid |
| `≤ 1024px` | Tablet | Sections stack, a 2×2 search bar, a two-column destination grid, two pricing cards per row, a full-width newsletter |
| `≤ 600px` | Mobile | A single column throughout, the hamburger icon replaces the nav links, the search fields stack, the cards are full width |

---

## 📂 Project Structure

```
assignment2-b9/
├── index.html        # Page markup
├── css/
│   └── style.css     # All styles + responsive media queries
└── Images/           # Destination photos, icons and logo
```

---

## 🚀 Run Locally

```bash
git clone https://github.com/shimul705/assignment2-b9.git
cd assignment2-b9
```

Then open `index.html` in any browser. No build step is required.

> **Note:** the embedded YouTube video may show "Error 153" when the file is opened directly from disk (`file://`). It plays normally on the live site or through a local server such as VS Code Live Server.

---

## 📚 What I Learned

- Building gallery layouts with mixed card sizes using **CSS Grid** (`grid-template-columns`, `fr` units, `span`).
- Centring overlay text with **`position: absolute` + `transform: translate(-50%, -50%)`**.
- Designing **pricing cards** with gradients and box shadows.
- Embedding and sizing **YouTube videos** responsively.
- Writing **tablet and mobile breakpoints** for a multi-section page.
- Reusing utility classes (`.primary-button`, `.peragraph`, `.section-head`) to keep styles consistent.

---

## 👤 Author

**Shimul**
GitHub: [@shimul705](https://github.com/shimul705)

---

<sub>Part of my Programming Hero learning journey. Each assignment shows a step in my growth as a web developer.</sub>
