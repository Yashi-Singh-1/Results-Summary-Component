# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Hey there! I build a results summary component using just HTML and CSS. The key is to make sure it looks great on any screen size, so it's super important to nail that responsive design. Oh, and don't forget those hover effects—they really make things pop! Ready to create a slick, interactive interface? Let's do this!

### Screenshot

Desktop Preview

![Desktop Preview](image/Desktop-Preview.png)

Mobile Preview

![Mobile Preview](image/Mobile-Preiew.png)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- External dependencies:
      - Google Fonts: Imported 'Hanken Grotesk' font via URL in CSS for typography.
      - Local Images: Utilized <img> tags with local image sources (image/icon-reaction.svg, etc.) for graphical content.


### What I learned

Working on this project has been a great learning experience, and here are some key takeaways:

#### Semantic HTML5 Markup
Using semantic elements like <section>, <div>, <h3>, and <p> helped me structure the content meaningfully. Here's an example of how I used semantic elements effectively:
<pre>
<section class="summary">
  <h3>Summary</h3>
  <!-- Other semantic elements used here -->
</section>
</pre>
#### CSS Custom Properties (Variables)
CSS custom properties (--variables) proved invaluable for maintaining consistent styling across the project. Here's how I defined and used them:
<pre>
:root {
  --light-red: hsl(0, 100%, 67%);
  --orangey-yellow: hsl(39, 100%, 56%);
  /* Define other variables */
}

.result .great {
  color: var(--orangey-yellow);
}
</pre>

#### Flexbox for Responsive Layouts
Flexbox (display: flex) was crucial for creating flexible layouts, especially within the .container and .result sections. It simplified alignment and distribution of elements:
<pre>
.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.result {
  flex: 1;
  text-align: center;
}
</pre>
#### Media Queries for Mobile-First Design
Implementing media queries (@media (max-width: 630px)) ensured the design was responsive and optimized for various screen sizes. Here's how I adjusted styles for smaller screens:
<pre>
@media (max-width: 630px) {
  .result .score {
    width: 35vw;
    height: 35vw;
  }
  
  /* Other responsive adjustments */
}
</pre>
#### External Dependencies Management
Integrating Google Fonts and local images (<img> tags) required understanding how to link external resources and optimize loading times:
<pre>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Hanken+Grotesk:ital,wght@0,100..900;1,100..900&display=swap">

<img src="image/icon-reaction.svg" alt="Reaction Icon" width="24" height="24">
</pre>
These learnings have not only improved my understanding of front-end development but also enhanced my ability to create responsive, visually appealing web interfaces using modern HTML and CSS techniques.

## Author

- LinkedIn - [Yashi Singh](https://www.linkedin.com/in/yashi-singh-b4143a246)
- Frontend Mentor - [@Yashi-Singh-1](https://www.frontendmentor.io/profile/Yashi-Singh-1)
