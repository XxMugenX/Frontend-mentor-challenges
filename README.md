# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)
  -  [Useful Resources](#Useful-Resources)

## Overview

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex

### What I learned

how to centre a div vertically and horizontally using margin auto and align-items

```html
<h1>Some HTML code I'm proud of</h1>
<div class="qrcode-box">
    <div class="qr-img"><img class="image" src="./images/image-qr-code.png"></div>
    <div class="qr-details">
      <h3>Improve your front-end skills by building projects</h3>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </div>
```
```css
body{
    display:flex;
    background-color: rgb(213, 226, 240) ;
    align-items: center;
    flex-direction: column;
    height: 100vh;
}
```

### Continued development

different displays and how to manipulate them

### Useful resources

- [Example resource 1](https://www.w3schools.com) -  this really helped me understand the object-fit property


## Author
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/XxMugenX)

