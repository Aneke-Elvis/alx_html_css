# CSS Basics Project

## Description
This project extends the **HTML Basics** work by adding styling with **CSS** and introducing **Flexbox** for positioning. It also covers the basics of **responsive web design**, ensuring the site adapts to different screen sizes.

---

## Task Requirements

1. **Early Styling**
   - Create a new `css_basic` directory inside the repository.
   - Copy `index.html` and `tweets.html` from the `html_basic` project.
   - Add two CSS files:
     - `base.css` (starter styles provided).
     - `styles.css` (custom styles).
   - Link both CSS files in the `<head>` of each HTML page.

2. **Positioning with Flexbox**
   - Use `display: flex` to structure the layout.
   - `<body>` uses `flex-direction: column` for header, main, and footer.
   - `<main>` uses `flex-direction: row` to place `<article>` and `<aside>` side by side.
   - Proportions: `<article>` takes 2/3 width, `<aside>` takes 1/3.
   - Enable scrolling with `overflow-y: auto`.

3. **Responsive Design**
   - Add `class="works_on_smartphone"` to the `<body>` tag.
   - Include the viewport meta tag:
     ```html
     <meta name="viewport" content="width=device-width, initial-scale=1">
     ```
   - Layout stacks properly on smaller screens for better usability.

---

## Extra Notes
- `base.css` provides predefined styles that help with mobile-friendly behavior.  
- `styles.css` is used for Flexbox layout rules and can be extended for custom styling.  
- Testing in browser dev tools (mobile view) is recommended to confirm responsiveness.  



