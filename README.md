# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshots/desktop-version.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML and CSS
- Flexbox
- Mobile-first workflow

### What I learned

I learned alot from just this one project.
The different ways to use flexbox, SVGs, using the correct media queries, Google Font and, the CSS property i never used before; `min-height`.

So i stumbled upon a lot of problems while trying to finish this project, even though i solve most of the troubles by just experimenting on different codes and different approaches, but still there's this one problem, the whole card is shrinking vertically on my own preview (without the developer tools/toggling the device toolbar). I tried to google it, but i just don't know what to search. After spending hours just staring at the screen, i finally got it #eurekamoment. It turns out to be a problem that's really easy to solve. Using `min-height` property bypass the `height: 80%` that i use for its container. 


```css
.the-container {
  height: 80%;
}

.proud-of-this-css {
  min-height: 560px;
}
```
Wassup my future self

### Continued development

I would say that i've done a pretty good job here but it could be better remembering that all the workflow and layout was designed in my head.
Definitely would try to design the layout first before starting to code with a tool like Figma or just pen and paper.
Custom CSS properties or Sass maybe? 

### Useful resources

- [Center Me Lad Land by Abdalla Arbab](https://glitch.com/~center-me-lad-land) - "this project is made to end all center me vertically and horizontally CSS madness in the world!"

- [Devcord | Discord](https://discord.gg/devcord) - An amazing discord server, highly recommend you to check it out.

- [Kevin Powell | Youtube](https://www.youtube.com/kepowob) - The king of CSS for real.

## Author

- Frontend Mentor - [@onyi-106](https://www.frontendmentor.io/profile/onyi-106)
- Instagram - [@ridho.nyi](https://www.instagram.com/ridho.nyi/)

## Acknowledgments

Big shout out to Kevin Powell and all members of Devcord lets goooo