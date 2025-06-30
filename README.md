# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Screenshot](https://github.com/user-attachments/assets/d2a8e7eb-4d9d-4cab-981c-140e1cc17cdd)

### Links

- ![Solution URL](https://www.frontendmentor.io/solutions/product-preview-card-component-UON53Br42E)
- ![Live Site URL ](https://product-preview-card-component-brown-nu.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

✅ Instead of using two <img> elements and then toggling them using css, you could use the <picture> element, buddy.

✅ The <picture> element is super handy cuz it lets you show different images depending on the screen size or device.

✅ Let's break it down with this example:

```
<picture>
  <source srcset="images/image-product-desktop.jpg" media="(min-width: 768px)">
  <img src="images/image-product-mobile.jpg alt="A beautiful perfume">
</picture>
```

✅ This ensure to display the image put in the <source> as long as the page is larger than 768px otherwise it goes to the default path set in the img, which will be for mobile.

### Continued development

### Useful resources

## Author

- Website - [Farzaneh Kazemi](https://verdant-bienenstitch-220a6d.netlify.app/)
- Frontend Mentor - [@Farzane2630](https://www.frontendmentor.io/profile/Farzane2630)
- StackOverflow - [@farzane-kazemi](https://stackoverflow.com/users/19888516/farzane-kazemi)

## Acknowledgments
