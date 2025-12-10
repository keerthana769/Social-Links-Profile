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


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screenshot%20(335).png)

### Links

- Solution URL: [Add solution URL here](https://github.com/keerthana769/Social-Links-Profile/)
- Live Site URL: [Add live site URL here](https://keerthana769.github.io/Social-Links-Profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned that it's not always necessary to give images a width: 100%; using the appropriate size for the layout works just as well. I also focused on writing cleaner and more semantic code without unnecessary repetition, and I feel more confident about structuring HTML properly.

I also discovered that numeric font-weights (like 700) only work when the corresponding weight is imported from Google Fonts. If a weight isn’t included in the import, you can use standard keywords such as bold instead.


I learned the difference between :focus and :focus-visible, which is important for accessibility and keyboard navigation:

:focus
This state appears whenever an element receives focus, whether through a mouse click, keyboard navigation, or script. It’s useful for general interaction, especially for form inputs.

:focus-visible
This state appears only when the browser determines that a focus indicator should be shown—typically during keyboard navigation using the Tab key. It helps provide clear visual cues for keyboard users without showing unwanted outlines for mouse interactions.

```html
  <link href="https://fonts.googleapis.com/css2?family=Figtree:ital,wght@0,300..900;1,300..900&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap" rel="stylesheet">

```
```css
nav a button{
  background-color: hsl(0, 0%, 20%);
  border: none;
  width: 100%;
  padding: 12px;
  border-radius: 8px;
  font-weight: bold;
  font-size: 14px;
}

a:focus{
  color: hsl(0, 0%, 8%);
  cursor: pointer;
  background-color: hsl(75, 94%, 57%);
}

a:{
  text-decoration: none;
}
```

### Continued development

For now, I’ve added a simple HTML placeholder page in place of my portfolio. Once I finish learning the skills I need to build a complete portfolio website, I plan to replace it with a fully designed and functional version.

I also want to improve the accessibility of my projects, especially when it comes to link text. In future projects, I plan to add more descriptive or visually hidden text so that these links provide clearer meaning and a better experience for users who rely on assistive technologies.

### Useful resources

- [Resource 1](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:focus-visible/) - This resource helped me learn how to highlight navigation through keyboard.

## Author

- Frontend Mentor - [@keerthana769](https://www.frontendmentor.io/profile/keerthana769)
- LinkedIn - [@keerthana-gurram](https://www.linkedin.com/in/keerthana-gurram/)

