# Frontend Mentor - Base Apparel Coming Soon Page

This is my solution to the [Base Apparel coming soon page](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0) challenge on Frontend Mentor.  
The goal: to build a *coming soon* page that is fully responsive with accessible email validation.

---

## 🗂️ Table of Contents
- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Future Improvements](#future-improvements)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

---

## Overview

### The Challenge
Users should be able to:
- View the optimal layout depending on their screen size  
- See hover and focus states for interactive elements  
- Receive an error message when:  
  - The input field is empty  
  - The email address format is invalid  

### Screenshot
![Preview](./screenshot.jpg)

### Links
- 🧠 Solution: https://www.frontendmentor.io/solutions/...  
- 🌍 Live Site: https://your-username.github.io/base-apparel/ *(or Vercel)*  
- 📦 Repository: https://github.com/your-username/base-apparel  

---

## My Process

### Built With
- **Semantic HTML5** (structured titles, visually hidden label, `aria-live`)  
- **CSS3**: custom properties, 2-column **Grid**, **Flexbox** for the form, `clamp()` for typography, `color-mix()` with **oklab**, and gradients  
- **Mobile-first** workflow with responsive media queries  
- **Vanilla JavaScript** for form validation  

---

### What I Learned
- Mastered responsive image techniques with the `<picture>` element and `object-fit`/`object-position` to make the hero image adapt perfectly across devices.
- Learned how to use color mixing with the `color-mix()` function in CSS to create accessible color variations.
- Email validation using HTML5 (`type="email"`, `required`) and JavaScript (`input.validity`)  
- Managing accessible error messages with `aria-live="polite"`  
- Styling form inputs based on their states (`:invalid`, `:focus`, etc.)  
- Using the modern `:has()` pseudo-class to style the button dynamically:
  ```css
  form:has(input:invalid) button { 
    background: var(--red); 
  }


### Future Improvements
- Add animations (ex: smooth appearance of the error message)
- Improve accessibility (ex: clearer focus outline on the button)
- Add unit tests for JavaScript validation
- Rebuild the project with a JavaScript framework (ex: React) for better structure
- Connect a backend to store user emails in a database
- Optimize hero images with modern formats (ex: WebP, AVIF) for better performance
- Add a dark mode toggle for user preference

### Useful Resources
- [Using the Constraint Validation API](https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Constraint_validation) - MDN
- [CSS :has() pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/:has) - MDN
- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - CSS-Tricks

## Author
- Lea Francois – Web development student at Wild Code School, currently learning fullstack development.

## Remerciements
Merci à Frontend Mentor pour ces challenges qui m’aident à progresser ! 🚀