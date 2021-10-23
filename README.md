# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [https://github.com/marcus-hugo/huddle-landing-page-with-single-introductory-section-master](https://github.com/marcus-hugo/huddle-landing-page-with-single-introductory-section-master)
- Live Site URL: [https://marcus-hugo.github.io/huddle-landing-page-with-single-introductory-section-master/](https://marcus-hugo.github.io/huddle-landing-page-with-single-introductory-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Second time working from a Sketch file.  Kept responsiveness in mind using flexbox and percentages on the svg image `width: 90%;`, and on desktop layout `max-width: 35%;` on the `.inner-container`.  Initially started with a `display: grid;` layout for desktop, but, found that flexbox was much better.  Had to trial and error getting the `background-image` positioned so that it covered the viewport without distorting its aspect ratio, this is what I settled on:

```css
background-position: 0 0;
background-size: auto 100vh;
```

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development
Would like to practice uising BEM for my next project.  I am currently taking Kevin Powell's course Conquering Responsive Layouts. 

https://courses.kevinpowell.co/conquering-responsive-layouts



### Useful resources



## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@marcus-hugo](https://www.frontendmentor.io/profile/marcus-hugo)



## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.