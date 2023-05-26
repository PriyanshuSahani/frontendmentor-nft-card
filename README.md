# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

### Screenshot

![Desktop view](./Output/live-site-ss.png)

### Links

- Solution URL: [Github Repository](https://github.com/PriyanshuSahani/frontendmentor-nft-card)
- Live Site URL: [Live site](https://priyanshusahani.github.io/frontendmentor-nft-card/)

## My process

- Analysed the required layout to determine how I need to structure my HTML.
- Created the HTML, optimally using divs and section to simplify the CSS file.
- Finally, in style.css:
	- First setup the root variables
	- Applied the CSS reset
	- Built the layout(Positioning and sizing the divs)
	- Added colors and fonts.
	- Finished by applying hover effects.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned about handling images in CSS.<br>
Getting the hover effect on the image was the most difficult part about the project.

```
.nft-bg {
    background-color: rgba(0, 255, 247, 0.5);
    background-image: url(images/image-equilibrium.jpg);
    background-size: contain;
    width: 100%;
    aspect-ratio: 1;
    max-height: 300px;
    border-radius: 8px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
}
.nft-image {
    width: 20%;
    z-index: -1;
}
.nft-bg:hover,
.nft-image:hover {
    cursor: pointer;
    background-blend-mode: lighten;
    /* opacity: 0.5; */
    z-index: 0;
}
```

This part of the CSS took me the most time to implement as not only I had to write the css to have something look a particular way but couldn't figure out what were the micro changes that were needed on hover. There might be a more optimal approach to do so.
Suggest if you find one.

### Continued development

I look forward learn javascript and build theme swithing web pages.



## Author

- Frontend Mentor - [PriyanshuSahani](https://www.frontendmentor.io/profile/PriyanshuSahani)


