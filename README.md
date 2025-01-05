# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./images/Blog%20desktop.png)
![](./images/Blog%20desktop%20hover.png)
![](./images/Blog%20mobile.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Float

### What I learned

So i kinda struggle with the image at first cause i thought it was an svg and that made thing difficult 
but i realised i didn´t to use the svg i can use an img tag and it worked perfectly. Also thanks to the last project i got best in using postioning to center the content and this time i added Flexbox. like the last project i had to try a lot of value for the width, height, padding, and margin before i can get the right one
Lastly this is my first time officially working with box shadow i`ve had a few class on it but this is the the first time writing it in my code and i loved how it turned out 

To see how you can add code snippets, see below:


```css
.main-container {
    background-color: hsl(0, 0%, 100%);
    width: 310px;
    height: 480px;
    border: 1px solid black;
    border-radius: 15px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    box-shadow: 6px 5px 3px 1px rgba(
        0, 0, 0, 0.9);
}

.main-container > .sub-container > .profile > img {
    width: 40px;
    margin-right: 10px;
    float: left;
}

span {
    font-family: "Figtree", serif;
    font-weight: 700;
    margin-top: 10px;
    float: left;
}
```

### Continued development

i will focusing on how to get the right value in terms of px and % also how to align contents better 
how to use Flexbox in place of float and to add favicon.


## Author

- Website - [Stephen Makinde](tiktok @grammy_inc)
- Frontend Mentor - [@Stephengrammy](https://www.frontendmentor.io/profile/Stephengrammy)
- Twitter - [@grammy_dev](https://www.twitter.com/@grammy_dev)

