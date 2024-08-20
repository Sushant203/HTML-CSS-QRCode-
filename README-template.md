# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Links

- Solution URL: (https://github.com/Sushant203/HTML-CSS-QRCode-)
- Live Site URL: (https://qr-code-challange101.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

While completing this challange, I've learned to center the div in a proper manner and also i've learned box shadow property and it's attributes and to apply it in the code.

To use box shadow property of CSS, see below:

```html
<div class="container">
      <img src="images/image-qr-code.png" alt="qr-code-image" class="qr-img">
      <section class="qr-text">
        <h4 id="qr-heading">Improve your front-end skills by building projects</h4>
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </section>
    </div>
```
```css
.container {
      border-radius: 20px;
      width: 300px;
      height: 485px;
      background-color: white;
      text-align: center;
      padding: 16px 16px 40px;
      box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
    }
```

### Continued development

I want to continue development in the areas like making code more symantically correct and using CSS more to design the page more easily in the future challange projects.


### Useful resources

- [MDN DOCS](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content) - This helped me for using justify property to center my div. I really liked this property and will use it going forward.


## Author

- Website - [Sushant Shrestha](https://github.com/Sushant203/HTML-CSS-QRCode-)
- Frontend Mentor - [Sushant Shrestha](https://www.frontendmentor.io/profile/Sushant203)

