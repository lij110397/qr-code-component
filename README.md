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

## Overview

This is a practice work for learning html and css basic. This project is to make a QR code component.

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/lij110397/qr-code-component)
- Live Site URL: [Add live site URL here](https://lij110397.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

**1. The process of turning a figma design into html and css files.**
- plan through the project
- complete basic html files - include all elements related to content
- complete general style  - include color and typography
- complete layout setting - include the size and layout
- test and make the design responsive - Inspect in the browser to check from min-size to check if it is responsive; fix the code
- check if it meets WCAG requirements and fix the code
- complete README.md

**2.practice how to add online font into the page**
```html    
<link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style.css" />
```
```css
.outfit-normal,
.outfit-bold {
  font-family: "Outfit", sans-serif;
  font-optical-sizing: auto;
  font-style: normal;
}

.outfit-normal {
  font-weight: 400;
}

.outfit-bold {
  font-weight: 700;
}
```

**3. how to use val to define global color**
```css
:root {
  --color-primary: #2c7dfa;
  --color-primary-shade: #3685ff;
  --color-dark-navy: #1f314f;
  --color-grey: #7d889e;
  --color-light-grey: #d5e1ef;
}
```
**4. how to use github pages**
This is the first time for me to use github pages which is interesting and effective.

### Continued development

1. How to manage layout in a more effective way?
I was struggling to choose between flexbox and grid systems. Sometimes, I thought it was ok to use both but it was not. It is still confusing to me.

2. How to manage margin and fix margin collapse?
I thought margin collapse would happen naturally, but in this case margin between elements are not doing margin collapse. Instead, the margin between the elements are added together. I am still confusing how to manage the margin to make it neat.

### Useful resources

- [Resource 1](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/Styling_text/Web_fonts) - This helped me for adding online google font into my files.
- [Resource 2](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/Building_blocks/Organizing) - This inspires me to better organize the selectors in my css files.

## Author

- Website - [Jiao Li]

