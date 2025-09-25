# Frontend Mentor - Tech Book Club Landing Page

This is a solution to the [Tech Book Club Landing Page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/tech-book-club-landing-page-fZQidjHU73). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

This is a fully responsive, modern landing page built with **HTML5**, **CSS3** (custom properties, responsive grid, flexbox, utility classes), and bundled with **Vite**. The design follows accessibility best practices and includes semantic markup, reusable components, and clean, minimal UI.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Mobile Screenshot](#mobile-screenshot)
  - [Tablet Screenshot](#tablet-screenshot)
  - [Desktop Screenshot](#desktop-screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Features](#features)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements
- Navigate content that is accessible and semantic
- Explore membership cards with responsive layouts

### Mobile Screenshot

![](/public/screenshots/mobile-screenshot.png)

### Tablet Screenshot

![](/public/screenshots/tablet-screenshot.png)

### Desktop Screenshot

![](/public/screenshots/desktop-screenshot.png)

### Links

- Live Site URL: [Tech Book Club Landing Page](https://fem-tech-book-club-landing-page.vercel.app/)

## My process

### Features

- Responsive layout for **mobile → desktop** (grid + flexbox)
- Utility classes for typography, spacing, and text colors
- Semantic, accessible HTML structure (`<header>`, `<section>`, `<footer>`)
- Membership cards with pricing and CTA buttons
- Testimonials section with star ratings
- Call-to-action (CTA) with responsive background
- Hover and focus states for interactive elements
- Assets optimized for mobile, tablet, and desktop (using `<picture>`)

### What I Learned

---

#### Accessibility

- Used semantic HTML elements (`<header>`, `<main>`, `<section>`, `<footer>`) for better structure.
- Implemented a `.visually-hidden` class for screen-reader-only text.
- Respected `prefers-reduced-motion` to improve accessibility for motion-sensitive users.

#### Modern CSS

- Leveraged **CSS custom properties** for colors, typography scales, and spacing.
- Built a **utility-first CSS approach** (`.flow`, `.container`, `.btn`, `.list--tick`) for consistency and reusability.
- Combined **CSS Grid** and **Flexbox** for responsive layouts.
- Used `background-clip: text` and gradients for modern text effects.

#### Component Styling

- Created reusable **card components** for membership tiers.
- Styled testimonials and CTA sections with consistent typography and layout utilities.
- Managed numbered lists with CSS counters.

#### Tooling

- Project scaffolded with **Vite** for fast builds and local dev server.
- Organized assets (`/public/images/`) and styles (`/src/style.css`) for scalability.

## Author

Github - [Lewis](https://github.com/Lewis-mbui)  
Frontend Mentor - [@Lewis-mbui](https://www.frontendmentor.io/profile/Lewis-mbui)
