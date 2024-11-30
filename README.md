# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
      - [Mobile view](#mobile-view)
      - [Desktop view](#desktop-view)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

#### Mobile view

![](./sources/screenshots/Mobile%20view.png)

#### Desktop view

![](./sources/screenshots/Desktop%20view.png)

### Links

- Solution URL: [Recipe page Responsive Design by HTML5 and Sassy CSS (Sass)](https://www.frontendmentor.io/solutions/recipe-page-responsive-design-by-html5-and-sassy-css-sass-_FFCZSPcl4)
- Live Site URL: [Frontend Mentor | Recipe page](https://vangmanawkairung.github.io/Frontend-Mentor_recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS (Sassy CSS)
- CSS custom properties
- Mobile-first workflow
- Responsive Design Techniques
- Flexbox
- CSS Grid
- Google Fonts
- Accessibility Best Practices

### What I learned

This challenge improved my skills in writing semantic HTML5 and crafting accessible designs using ARIA attributes. I learned to use SCSS for cleaner, scalable styles with variables, nesting, and a mobile-first workflow. Applying Flexbox and CSS Grid allowed me to create a responsive, well-structured layout.

This SCSS snippet showcases my use of variables, nesting, and custom styles for the preparation section:

```
.prepare-info {
  background-color: $prepare-section-background-color;
  padding: 25px;
  border-radius: 10px;

  h3 {
    font-size: 1.2rem;
    color: $prepare-section-heading-and-bullet-color;
  }

  ul li::marker {
    color: $prepare-section-heading-and-bullet-color;
    font-weight: $bold-text-font-weight;
  }
}

```

I’m proud of how this code is organized, reusable, and visually consistent. This project strengthened my skills in building clean, responsive, and accessible web pages.

### Continued development

I plan to continue improving my skills by exploring more advanced concepts like animations, transitions, and responsive typography. For future projects, I want to deepen my understanding of accessibility standards, experiment with modern tools like CSS variables alongside SCSS, and integrate JavaScript to add interactivity. Each challenge is an opportunity to refine my workflow and create better, more user-friendly web experiences.

### Useful resources

- [CSS Lists](https://www.w3schools.com/css/css_list.asp) - This website demonstrates how to style the list basically.
- [::marker](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker) - This page shows how to assess the list marker by using psuedo element `marker`.

## Author

- Frontend Mentor - [@VangmanawKairung](https://www.frontendmentor.io/profile/VangmanawKairung)
- GitHub - [VangmanawKairung](https://github.com/VangmanawKairung)

## Acknowledgments

I would like to express my gratitude to **Frontend Mentor** for providing this challenge, which helped me enhance my skills and gain valuable hands-on experience. A big thanks to **VSCode** for being my go-to code editor with its powerful extensions and productivity features. The **Preview app on macOS** and **Chrome Developer Tools** were indispensable for testing and fine-tuning my design. I also appreciate the wealth of resources available online, from tutorials to documentation, that guided me through this project. Lastly, a heartfelt acknowledgment to all the tools, platforms, and communities that support developers in creating and learning every day!
