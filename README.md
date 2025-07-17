# CSS5
CSS (Cascading Style Sheets) is used to style and design HTML content on the web. It controls layout, colors, fonts, spacing, and responsiveness. CSS makes websites visually appealing and user-friendly. It supports animations, media queries, and frameworks like Bootstrap. Ideal for clean, responsive UI design.

# 🎨 CSS Deep-Dive – Days 5 to 10

This guide includes everything you need to understand CSS from fundamentals to advanced techniques with practical examples and a responsive mini project.

---

## ✅ Day 5: CSS Fundamentals

### Key Topics:
- **What is CSS?** – Styling language for HTML
- **How to Add CSS**
  - Inline: `style=""`
  - Internal: `<style>` tag
  - External: linked `.css` file
- **CSS Syntax**
  ```css
  selector {
    property: value;
  }
  ```
- **Selectors**: Element, Class, ID, Group, Universal, Descendant
- **Units**: `px`, `em`, `rem`, `%`, `vh`, `vw`
- **Colors**: Names, HEX, RGB, HSL
- **Text Styling**: `font-size`, `font-family`, `color`, `line-height`
- **Box Model**: `margin`, `border`, `padding`, `content`
- **CSS Comments**: `/* comment */`

---

## ✅ Day 6: Layout & Positioning

### Key Topics:
- **Display**
  - `block`, `inline`, `inline-block`, `none`
- **Positioning**
  - `static`, `relative`, `absolute`, `fixed`, `sticky`
- **Float & Clear**
- **Overflow**
  - `visible`, `hidden`, `scroll`, `auto`
- **Z-index**
  - Controls stacking order of overlapping elements

---

## ✅ Day 7: Box Model & Flexbox

### Box Model:
- Explains how spacing around elements works
- `box-sizing: border-box` is recommended

### Flexbox (1D Layout):
- `display: flex`
- Direction: `flex-direction: row/column`
- Alignment:
  - Main axis: `justify-content`
  - Cross axis: `align-items`
- Wrapping: `flex-wrap`
- Gap: `gap`
- Individual control: `flex-grow`, `flex-shrink`, `flex-basis`, `order`

---

## ✅ Day 8: Advanced CSS Topics

### CSS Variables (Custom Properties):
```css
:root {
  --main-color: #007bff;
}
button {
  color: var(--main-color);
}
```

### Pseudo-Classes:
- `:hover`, `:active`, `:focus`, `:nth-child(n)`

### Pseudo-Elements:
- `::before`, `::after`, `::first-letter`

### CSS Transitions:
```css
transition: all 0.3s ease-in-out;
```

### CSS Animations:
```css
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}
```

---

## ✅ Day 9: Grid, Flexbox & Responsive Animations

### CSS Grid:
- 2D layout system
- Properties:
  - `display: grid`
  - `grid-template-columns`, `grid-template-rows`
  - `gap`, `grid-area`, `grid-column`, `grid-row`

### Flexbox vs Grid:
- Use **Flexbox** for 1D layouts (row or column)
- Use **Grid** for 2D layouts (rows + columns)

### Responsive Animations:
- Use `transform` and `opacity` for performance
- Use media queries for responsive motion
- Respect user preferences:
```css
@media (prefers-reduced-motion: reduce) {
  * {
    animation: none !important;
    transition: none !important;
  }
}
```

---

## ✅ Day 10: Responsive UI Components & Final Project

### Reusable UI Components:
- Responsive Navigation Bar
- Cards with hover animation
- Hero section with CTA
- Footer with social links
- Optional: Modal (CSS or JS toggle)

### Final Project – Mini Landing Page:
- **Header**: Logo + Nav
- **Hero Section**: Title, Text, Image, CTA Button
- **Features**: 3 Cards with icons/text
- **Testimonials**: Grid layout
- **Footer**: Contact + Social Icons

### Tools Used:
- Flexbox & Grid
- CSS Variables
- Animations
- Responsive Design (media queries)
- Component-based layout

---


---

## 🏁 Conclusion

You’ve now mastered:
- CSS from basic styling to responsive design
- Building components using modern layout techniques
- Animating your UI smoothly and accessibly
- Structuring a full mini project using HTML + CSS



**Happy Styling! 🎨**
