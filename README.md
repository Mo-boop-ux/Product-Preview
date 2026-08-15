# Frontend Mentor - Product Preview Card Component Solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements (such as the "Add to Cart" button)
- View accurate typography, responsive product image presentation, and clean pricing layout

### Links

- **Live Site URL**: [Live Demo](https://mo-boop-ux.github.io/Product-Preview/)
- **GitHub Repository**: [Product-Preview](https://github.com/Mo-boop-ux/Product-Preview)

---

## My Process

### Built With

- **Semantic HTML5** markup
- **CSS Flexbox** - For two-column desktop card layout and vertical mobile stacking
- **Google Fonts** - [Montserrat](https://fonts.google.com/specimen/Montserrat) & [Fraunces](https://fonts.google.com/specimen/Fraunces)
- **Responsive Design** - Media queries for fluid adaptation between mobile and desktop viewports
- **Interactive States** - Custom styled button with hover and active states

### What I Learned

During this challenge, I worked with product card layout ergonomics, typography pairing, and responsive button design:

1. **Two-Column Card Alignment**:
   Distributing product image and text content equally within the card container:

```css
.main-component {
    background: #ffffff;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 10px;
    overflow: hidden;
}

.image, .content {
    width: 50%;
}
```

2. **Typography & Hierarchy**:
   Pairing sans-serif tracking labels with serif headings and striking price typography:

```css
.content p {
    font-size: 12px;
    text-transform: uppercase;
    letter-spacing: 5px;
    color: #6c7289;
}
```

### Useful Resources

- [MDN Web Docs - Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
- [Frontend Mentor](https://www.frontendmentor.io)

---

## Author

- GitHub - [Mo-boop-ux](https://github.com/Mo-boop-ux)
- Frontend Mentor - [@Mo-boop-ux](https://www.frontendmentor.io/profile/Mo-boop-ux)
