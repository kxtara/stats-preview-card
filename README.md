# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

I completed this challenge faster than usual because I've done similar challenges on FEM.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![ScreenShot](https://raw.github.com/kxtara/stats-preview-card/main/images/desktop.jpg)

### Links

- Solution URL: [(https://www.frontendmentor.io/solutions/stats-preview-card-using-flexbox-wtXMwed-wH)]
- Live Site URL: [(https://kxtara.github.io/stats-preview-card/)]

## My process

I started with structuring the HTML, knowing that I'd need a flex container for the card, then followed with styling with CSS.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned that I don't have to re-arrange elements by using the position property and instead using the flex-direction and using row or column reverse.

```css
.card{
        flex-direction: row-reverse;
        align-items: center;
        justify-content: center;
        border-bottom-right-radius: 0;
        border-top-left-radius: 0.7rem;
        max-width: 60rem;
    }
```

### Continued development

Moving forward, I want to continue working with Flexbox and then go onto CSS Grid.

### Useful resources

- [Linux Hint](https://linuxhint.com/change-image-color-css/#:~:text=Combining%20the%20opacity()%20and,sepia%2C%20shadows%2C%20and%20more.) - This helped me with the coloring of the image.

## Author

- Frontend Mentor - [@kxtara](https://www.frontendmentor.io/profile/kxtara)
- Twitter - [@kiarahoheb](https://www.twitter.com/kiarahoheb)

