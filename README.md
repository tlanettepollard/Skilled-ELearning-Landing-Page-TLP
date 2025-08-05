# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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


#### Mobile View
![Mobile View](./assets/screenshots/MobileView.jpg)

#### Tablet View
![Tablet View](./assets/screenshots/TabletView.jpg)

#### Laptop View
![Laptop View](./assets/screenshots/MacBook%20Pro-1753477317625.jpeg)



### Links

- Solution URL: [Skilled E-Learning Solution]()
- Live Site URL: [Skilled E-Learning Live](https://tlanettepollard.github.io/Skilled-ELearning-Landing-Page-TLP/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS for style
- Flexbox
- CSS Grid: Courses section layout
- Desktop-first workflow


### What I learned

After watching Practical Web Dev's tutorial, I decided to code from a different perspective. Instead of coding and styling with "mobile-first" in mind, I used his approach by styling with "desktop-first". 

To see how you can add code snippets, see below:

```html
<!-- Hero Images -->
            <div class="hero-desktop-img">
              <img src="./assets/image-hero-desktop.webp" alt="hero desktop image">
            </div>
            <div class="hero-tablet-img">
              <img src="./assets/image-hero-tablet.webp" alt="hero tablet image">
            </div>
            <div class="hero-mobile-img">
              <img src="./assets/image-hero-mobile.webp" alt="">
            </div>
```
```css
 .hero-desktop-img {
            margin-right: -33rem;
            margin-top: -15rem;

            @include bp-laptop {
                display: none;
            }

        }

        .hero-tablet-img {
            display: none;

            @include bp-laptop {
                display: block;
                margin-right: -17rem;
                margin-top: -6rem;
            }

            @include bp-xl-tablet {
                margin-right: -20rem;
            }

            @include bp-sm-tablet-one {
                display: none;
            }

        }

        .hero-mobile-img {
            display: none;

            @include bp-sm-tablet-one {
                display: block;
                margin-top: 2rem;
            }

            @include bp-sm-mobile {
                width: 100%;
            }
        }
```


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Skilled E-Learning Landing Page Full Project Tutorial](https://www.youtube.com/watch?v=Bpmyy2nX_Pg) - This tutorial by Practical Web Dev helped me when I had difficulty styling the Hero image. 
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [T. Lanette Pollard](https://trista-lanette-pollard-portfolio.vercel.app/)
- Frontend Mentor - [@tlanettepollard](https://www.frontendmentor.io/profile/tlanettepollard)
- Twitter - [@TpLanetteNBCT](https://x.com/TpLanetteNBCT)
- BlueSky - [@tristalanpollard](https://bsky.app/profile/tristalanpollard.bsky.social)


## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
