# Frontend Mentor - QR code component solution by Tiago Neves

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
- [Acknowledgments](#acknowledgments)

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In this project I learn how to better display css elements using flexbox.

```html
 <section class="container">
        <div class="card">
            <div class="qrcode-card qrcode"></div>
            <h2>Improve your front-end skills by building projects</h2>
            <p>Scan the QR code to visit Frontedn Mentor and take your coding skills to the next level</p>
        </div>
    </section>
```
```css
.card{
    background: hsl(0, 0%, 100%);
    width: 220px;
    height: 350px;
    margin: 200px;
    border-radius: 15px;
}
.qrcode-card{
    height: 200px;
    margin: 10px;
    background-size: cover;
    border-radius: 7px;
}
.qrcode{
    background-image: url(./images/image-qr-code.png);
}
```

## Author

- Website - [Tiago Neves] 
- Frontend Mentor - [@TiagoNeves9](https://www.frontendmentor.io/profile/TiagoNeves9)
- Twitter - [@wydthiago](https://twitter.com/wydthiago)

## Acknowledgments

Special thanks to Cem Eygi Media for the very helpful video (https://www.youtube.com/watch?v=qXRYMdvq_Dc)


