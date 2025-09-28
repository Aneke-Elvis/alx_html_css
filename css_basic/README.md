# Webpage Layout and Styling Project

This project focuses on building a **responsive and modern webpage layout** using **CSS Flexbox** while implementing several specific styling requirements, including **edge-to-edge layout** and **custom table formatting**.

---

## 🎯 Goal & Key Features

The primary goal of this project is to restructure the traditional vertical stacking of HTML elements into a **full-height, column-and-row layout** using **nested Flexbox containers**.

### 📐 Layout Structure
- **`<body>` (Outer Container):**
  - `display: flex`
  - `flex-direction: column`
  - Stacks the **header**, **main content area**, and **footer** vertically.
  - Uses `min-height: 100vh` to ensure the footer always reaches the bottom.

- **`<main>` (Inner Container):**
  - `display: flex` with default `flex-direction: row`
  - Places `<article>` and `<aside>` side-by-side.
  - `flex-grow: 1` → Fills available vertical space between header and footer.

- **`<article>` (Content Area):**
  - Occupies **two-thirds (2/3)** of the width (`flex: 2`).

- **`<aside>` (Sidebar):**
  - Occupies **one-third (1/3)** of the width (`flex: 1`).

---

## 🎨 Styling & Resets

- **Edge-to-Edge Display:**
  - Universal reset `(*, ::before, ::after)` implemented.
  - Critical `html, body` reset with `!important` to remove margin/padding.
  - Ensures content touches all edges of the viewport.

- **Header Navigation:**
  - `flexbox` applied to `<nav>` and `<ul>`.
  - Aligns **logo to the left** and **menu links to the right**.

- **Table Styling:**
  - Clear **borders**, **padding**, and **distinct header backgrounds**.

- **Footer:**
  - Text explicitly aligned **to the left**.

- **Scrolling:**
  - `<article>` and `<aside>` set to `overflow-y: auto`.
  - Enables internal scrolling without affecting the full layout.

---

## 🛠️ Files

- **`index.html`** → Contains semantic HTML structure with `<main>`, `<article>`, and `<aside>`.
- **`new.css`** → Contains all CSS rules (resets, Flexbox, styling).

---

## 🚀 How to Run

1. Save the HTML as **`index.html`**.  
2. Save the CSS as **`new.css`** in the same directory.  
3. Open **`index.html`** in any modern browser.  

---

✅ You now have a **modern, responsive webpage layout** powered by **CSS Flexbox**.
