# Frontend Mentor - 3-column preview card component solution

This is a solution to the ![Design preview for the Profile card component coding challenge](./design/desktop-preview.jpg). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

[Desktop version](./design/desktop-design.jpg)
[Mobile version](./design/mobile-design.jpg)

### Links

- [Solution URL](https://github.com/TMraz/Challenges/tree/main/3-column-preview-card-component-main)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- MediaQuerries workflow
- [Styled Components](./css/style.css) - For styles

### What I learned

Snippets, see below:

```css
/* clearfix */
/*===================================================*/
.card:before,
.card:after {
    content: " ";
    display: table;
}
.card:after {
    clear: both;
}
.card {
    *zoom: 1;
}
/*=====================================================*/
```


### Useful resources

- [Float elements](https://developer.mozilla.org/en-US/docs/Web/CSS/float) - This helped me float the elements.