# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./design/desktop-design.png)
![](./design/mobile-design.png)

### Links

- Solution URL: [solution URL](https://github.com/lekaneniola476-commits/four-card-feature-section-master)
- Live Site URL: [live site URL]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned
What I learned

During this project, I improved my understanding of CSS Grid, especially how to create layouts using grid columns, rows, and named grid areas. I also learned how to use media queries to change the layout for different screen sizes.

One thing I found particularly useful was grid-template-areas, because it allows me to visually define where each element should be placed.
.boxes {
    display: grid;
    grid-template-columns: repeat(3, 1fr);

    grid-template-areas:
        ". team_builder ."
        "supervisor . calculator"
        ". karma .";
}
grid-template-columns: repeat(3, 1fr);
@media (max-width: 800px) {
    .boxes {
        grid-template-columns: repeat(2, 1fr);

        grid-template-areas:
            "team_builder supervisor"
            "calculator karma";
    }
}

@media (max-width: 600px) {
    .boxes {
        grid-template-columns: 1fr;

        grid-template-areas:
            "team_builder"
            "supervisor"
            "calculator"
            "karma";
    }
}




### AI Collaboration

I used ChatGPT as an AI assistant throughout the project, mainly for debugging, understanding CSS concepts, and exploring different solutions when I got stuck.

I used it particularly to:

Understand and troubleshoot CSS Grid layouts.
Learn how grid-template-columns, grid-template-rows, and grid-template-areas work.
Debug layout issues and understand why elements were overlapping or positioned incorrectly.
Get guidance on making the design responsive for tablet and mobile screen sizes.
Discuss different approaches before implementing them in my own code.

What worked well was using AI to explain why something was happening, rather than just giving me the code. This helped me understand concepts such as Grid alignment, responsive layouts, and media queries.

What didn't work as well was blindly applying suggested solutions. Some approaches caused new layout problems, so I had to test the changes in my browser, identify what wasn't working, and adjust the CSS. This taught me that AI suggestions still need to be tested and understood before being used.

## Author

- Website - [ENNY]()
- Frontend Mentor - [@lekaneniola476-commits](https://www.frontendmentor.io/profile/lekaneniola476-commits)
- Twitter - [@rising476](https://x.com/rising476)


