# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

![](./Solution%20Screenshot.png)

### Links

- Live Site URL: [URL](https://jemajr.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Glad to finally have a better understanding of css flexbox. This the css for the QR Code's content

```css
.content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 250px;
  margin: auto auto; /* Center the QR Code Component*/
  background-color: #fff;
  padding: 12px; /* white edge around the card */
  border-radius: 15px;
  box-shadow: 0 7px 30px rgba(0, 0, 0, 0.2);
}
```

### Continued development

- I'd like to get more comfortable turning a design into code (with more practice)
- I'd also like to get better with dimensioning for web projects

### Useful resources

- [Jonas Schmedtmann's Build Responsive Real-World Websites with HTML and CSS - Lesson on shadows](https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3) - This helped me with making the shadow behind the QR Code. I definitely still need more practice with this.


