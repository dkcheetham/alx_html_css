# Headphones Web Page

This project is part of the **ALX Frontend Curriculum**, and the objective is to **implement a web page from scratch** based on a Figma design provided by UI/UX designer **Nicolas Philippot**.

## 📄 Description

The goal is to replicate the design as closely as possible using **only HTML and CSS** — no JavaScript or external frameworks (like Bootstrap) are allowed.

This project puts into practice key web development concepts:

- Semantic HTML
- Responsive design
- CSS layout techniques (Flexbox, Grid)
- Accessibility best practices
- Design implementation based on a Figma file

---

## 🎯 Objectives

- Build a **fully responsive** and **accessible** web page.
- Match the layout and style of the provided **Figma design**.
- Follow best practices in web development and code structure.

---

## 🛠️ Requirements

- ✅ No use of JavaScript
- ✅ No use of external CSS frameworks (e.g., Bootstrap)
- ✅ Must use semantic HTML
- ✅ Implement responsive layout that adapts at **480px screen width**
- ✅ Max content width: **1000px**, centered on the page
- ✅ Buttons must have `opacity: 0.9` on hover/active
- ✅ Links must change to `#FF6565` on hover/active
- ✅ Must replicate visual layout from Figma accurately

---

## 🖼️ Design File

The original design was created by Nicolas Philippot.

> ✅ **[Figma File - Duplicate to Drafts](https://www.figma.com/file/XYZ)**  
> *(Make sure to be logged in and duplicate the file to access all design layers and measurements)*

If you can't access the fonts, they are available here:

- [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
- [Spin Cycle OT](https://www.fonts.com/font/spin-cycle)

> ⚠️ Some values in the Figma file are float numbers (e.g., 12.8px). You are free to round these values appropriately.

---

## 📁 Project Structure
alx_html_css/
└── headphones/
├── README.md
├── index.html # (to be created)
└── styles.css # (to be created)

---

## 💡 Notes

- Take the time to **study the Figma file** thoroughly. Pay attention to:
  - Font sizes and families
  - Spacing and alignment
  - Button states
  - Mobile layout (screen ≤ 480px)

- Make sure the layout remains usable and beautiful across devices.

---

## 📱 Responsive Design

When the screen width is `480px` or less:

- The page must automatically switch to the **mobile version** layout defined in the Figma file.
- Use media queries to implement this behavior.

---

## 🚀 Getting Started (for local development)

To view your project locally:

```bash
git clone https://github.com/dkcheetham/alx_html_css.git
cd alx_html_css/headphones
open index.html  # or use Live Server if using VS Code