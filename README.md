# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/mobile-first-landing-page-build-with-flex-and-grid-p5vkSylx7)
- Live Site URL: [Add live site URL here](https://shawncocklin.github.io/meet-landing-page/)

## My process

### Built with

- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

For this project, I had to make use of the ::before and ::after pseudo elements on my own for the first time. I used these to make the two numbers that had circles around them with a verticle line on the top:

```
.circle-number {
  position: relative;
  display: inline;
}

.circle-number::before {
  content: "";
  border: 1px solid #87879D;
  opacity: .25;
  height: 90px;
  position: absolute;
  top: -110px;
  left: 12px;
}

.circle-number::after {
  content: "";
  padding: 30px 30px;
  border: 1px solid #87879D;
  opacity: .4;
  border-radius: 100%;
  position: absolute;
  inset: 0;
  left: -19px;
  top: -19px;
}
```
I am happy with the solution I came up with, it looks pretty spot on and seems to maintain its look no matter what the screen size is. However, I could not quite figure out how to get the second one to overlap with the footer in teh same way as the design file shows. 

### Continued development

I would like to start writing more semantic HTML, and start making accessibility a much larger focus as I get more comfortable building out pages.

I also need to do more research and practice with background-image. I could not figure out how to achieve the same look for the footer that was in the design file.


## Author

- GitHub - [shawncocklin](https://github.com/shawncocklin)
- Frontend Mentor - [@shawncocklin](https://www.frontendmentor.io/profile/shawncocklin)

