# Frontend Mentor - QR code component solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iA_BxValidation).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./design/desktop-preview.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/Qusbee/qr-code)
- Live Site URL: [GitHub Pages](https://qusbee.github.io/qr-code/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (Variables)
- Flexbox
- BEM methodology
- Mobile-first workflow

### What I learned

During this project, I strengthened my core CSS and HTML skills:

1. **Font Loading Order:** Learned that `@import` directives must be placed at the very top of the CSS file before any universal selectors like `*`.
2. **Flexible Centering:** Used `min-height: 100dvh` instead of fixed `height` on the `body` element to ensure proper vertical centering on large screens while allowing smooth scrolling on smaller devices.
3. **BEM Naming Structure:** Practiced BEM methodology (`.card`, `.card__image`, `.card__content`, `.card__title`, `.card__text`) for clean, scalable, and maintainable CSS.
4. **Figma Shadows:** Accurately converted Figma shadow parameters (`drop-shadow`) into CSS `box-shadow` with `rgba` values for soft design reproduction.

```css
.card {
  box-shadow: 0 25px 25px rgba(0, 0, 0, 0.0477);
}```

## Author

- Frontend Mentor - [@Qusbee](https://www.frontendmentor.io/profile/Qusbee)
- GitHub - [@Qusbee](https://github.com/Qusbee)
