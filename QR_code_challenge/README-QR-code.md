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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Overview

### Screenshot

![](./QR_code_project.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS

### What I learned

Sizing this div was initially hard for me to figure out, as I didn't realize that I had to put it in a div with a height and width of 100% of the page. So I'm glad I was able to figure that out, even thought it took quite a while.

```html
<div style="background-color:white; height:50%; width:20%;" id="rectangle">
```

Even though it was mostly copied from the website mentioned below, it was still very satisfying to see it working and I'll implement it in the future now that I understand it.

```css
#rectangle {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  border-radius: 10px;
}
}
```

### Continued development

This probably doesn't work on mobile, but I'm not exactly sure how to test that yet. So I'd like to focus on that on my next project.

### Useful resources

- [W3schools](https://www.w3schools.com/) - This helped me for for fixing syntax errors since I haven't used HTML or CSS in a while. This website is incredibly useful and I'm sure I'll use it in the future.
- [Hubspot](https://blog.hubspot.com/website/center-div-css#center-div-vertically-css) - This is an amazing article which helped me finally understand how to center divs both horizontally and vertically. I'd recommend it to anyone still learning this concept.

## Author

- Github - [SabrinaGir](https://github.com/SabrinaGir)
- Frontend Mentor - [@SabrinaGir](https://www.frontendmentor.io/profile/SabrinaGir)


## Acknowledgments

My dad for trying his best to help me, even though his CSS is rusty ;)
