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
  - [Useful resources](#useful-resources)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Solution](/images/solution-image.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/HaiDangN/product-preview-card)
- Live Site URL: [Add live site URL here](https://haidangn.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to use `transition` in CSS to animate properties like `background-color`:

```css
.add-to-cart:hover {
    background-color: hsl(158, 42%, 18%); 
}
```

I also learned how to use a media query to make the layout responsive:
```css
@media (max-width: 600px) {
    .container {
      flex-direction: column;
      max-width: 350px;
    }
    .hero img {
        max-height: 275px;
        width: 100%;
        height: auto;
        object-fit: cover;
    }
}
```

### Useful resources

- [YouTube Tutorial](https://www.youtube.com/watch?v=rCBYZ7xn-us&list=PLcZZlEf3w738Bv45a8yI_iIv2OGx_JLvz) - This video helped me understand the workflow when recreating layouts. He gave me a simple framework to follow 
- [Example resource 2](https://www.example.com) - This was really helpful in showing me how experienced developers approach layout challenges. The video walked through a clear structure that I used as a reference when organizing my HTML and CSS.
