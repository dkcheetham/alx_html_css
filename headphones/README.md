# Headphones Web Page

This project is part of the **ALX Frontend Curriculum**, and the objective is to **implement a web page from scratch** based on a Figma design provided by UI/UX designer **Nicolas Philippot**.

## 📄 Description

The goal is to replicate the design as closely as possible using **only HTML and CSS** (with the exception of one task adding vanilla JavaScript for the hamburger menu) — no external frameworks (like Bootstrap) are allowed.

This project puts into practice key web development concepts:

- Semantic HTML  
- Responsive design  
- CSS layout techniques (Flexbox, Grid)  
- Accessibility best practices  
- Design implementation based on a Figma file  
- Basic JavaScript for UI interaction (hamburger menu)

---

## 🎯 Objectives

- Build a **fully responsive** and **accessible** web page.  
- Match the layout and style of the provided **Figma design**.  
- Follow best practices in web development and code structure.  

---

## 🛠️ Requirements

- ✅ No use of external CSS frameworks (e.g., Bootstrap)  
- ✅ Must use semantic HTML  
- ✅ Implement responsive layout that adapts at **480px screen width**  
- ✅ Max content width: **1000px**, centered on the page  
- ✅ Buttons must have `opacity: 0.9` on hover/active  
- ✅ Links must change to `#FF6565` on hover/active  
- ✅ Must replicate visual layout from Figma accurately  
- ✅ Use JavaScript only for hamburger menu toggle (no frameworks)  

---

## 🗂️ Project Structure and Task Summary
alx_html_css/
└── headphones/
├── README.md
├── 0-index.html # Task 0: Header
├── 0-styles.css
├── 1-index.html # Task 1: What we do
├── 1-styles.css
├── 2-index.html # Task 2: Our results
├── 2-styles.css
├── 3-index.html # Task 3: Contact us
├── 3-styles.css
├── 4-index.html # Task 4: Footer
├── 4-styles.css
├── 6-index.html # Task 5: Background image replacement
├── 6-styles.css
├── 7-index.html # Task 6: Animations
├── 7-styles.css
├── 8-index.html # Task 7: Hamburger menu
├── 8-styles.css
└── 8-script.js # JS for hamburger menu toggle


---

## 📋 Tasks Overview

| Task # | Feature                         | Files                   |
|--------|--------------------------------|-------------------------|
| 0      | Header                         | 0-index.html, 0-styles.css |
| 1      | What we do Section             | 1-index.html, 1-styles.css |
| 2      | Our Results Section            | 2-index.html, 2-styles.css |
| 3      | Contact Us Section             | 3-index.html, 3-styles.css |
| 4      | Footer Section                 | 4-index.html, 4-styles.css |
| 5      | Replace Background Image       | 6-index.html, 6-styles.css |
| 6      | Animations                    | 7-index.html, 7-styles.css |
| 7      | Hamburger Menu (JS)            | 8-index.html, 8-styles.css, 8-script.js |

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

## 📱 Responsive Design

When the screen width is `480px` or less:

- The page automatically switches to the **mobile version** layout defined in the Figma file.  
- Media queries are used to implement this behavior.  
- The hamburger menu is shown instead of the full navigation (for task 7).

---

## 🚀 Getting Started (for local development)

To view your project locally:

```bash
git clone https://github.com/dkcheetham/alx_html_css.git
cd alx_html_css/headphones
open 0-index.html  # or any index file for the task you want to view
# or use Live Server in VS Code for live reload