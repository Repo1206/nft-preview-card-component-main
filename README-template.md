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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

[](Screenshot 2023-06-21 132013.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned alot more about css then i planned to. I became a little more comfortable using display:flex, as well as making a hover effect.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.main-img {
  position: relative;
  height: 100%;
  width: 100%;
  border-radius: 0.8rem;
}
.main-img:hover {
  cursor: pointer;
  filter: grayscale(75%);
}
.container {
  position: relative;
}

.overlay-img {
  position: absolute;
  top: 35%;
  left: 50%;
  transform: translate(-50%, -35%);
  height: 10%;
  width: 10%;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.main-img:hover + .overlay-img {
  opacity: 1;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Resource 1](https://www.w3schools.com/) - This helped me figure out where i was going wrong with my css

## Author

- Website - [Phillip Estes](https://personal-site-puce-three.vercel.app/)
- Frontend Mentor - [@Repo1206](https://www.frontendmentor.io/profile/Repo1206)
- Twitter - [@Phillip_Estes20](https://www.twitter.com/Phillip_Estes20)
