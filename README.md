# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- The challenge is to build out a profile card component to match the provided designs and make sure it works well on different screen sizes. The project requires implementing flexbox layout and using background images effectively.

### Links

- Solution URL: [Github](https://github.com/yMeeraki/profile-card-component)
- Live Site URL: [Netlify](https://profilecard-fem.netlify.app)

## My process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Google Fonts (Kumbh Sans)

### What I Learned

In this project, I improved my understanding of using flexbox for creating responsive layouts. I also learned how to position and manipulate multiple background images using `background-position` and `background-size`. Here's an example of setting up multiple background images:

```css
body {
  background-image: url("./images/bg-pattern-bottom.svg"), url("./images/bg-pattern-top.svg");
  background-position: right 0% bottom -200%, left 0% top -200%;
  background-size: 40%, 40%;
}
```

### Continued development

In future projects, I plan to further explore:

- Accessibility improvements, ensuring better ARIA support and WCAG compliance.
- Working with CSS Grid for more complex layouts.
- Improving responsiveness on larger screens.

### Useful resources

- MDN Web Docs - CSS background property - This documentation helped me understand the use of multiple background images.
- Flexbox Froggy - A fun and interactive game that helped me grasp the concept of flexbox.

## Author

- Frontend Mentor - [@yMeeraki](https://www.frontendmentor.io/profile/yMeeraki)


