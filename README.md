# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](/my-solution.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

How to use Divs to group elements and sections in HTML to make positioning them easier using Flexbox in CSS

```html
<div class="card-container">
  <div class="card">
    <img src="images/image-qr-code.png" alt="image qr code" />
    <div class="text">
      <h3>Improve your front-end skills by building projects</h3>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </div>
</div>
```

```css
body {
  background-color: hsl(212, 45%, 89%);
  font-family: "Outfit", sans-serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  overflow: hidden;
  margin: 0;
}
```

## Author

- Frontend Mentor - [@Manny1023](https://www.frontendmentor.io/profile/Manny1023)
