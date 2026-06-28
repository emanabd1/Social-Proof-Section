# Frontend Mentor - Social proof section solution

This is my personal solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:
- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [Frontend Mentor Solution Page](https://www.frontendmentor.io/solutions/responsive-social-proof-section-using-css-grid-flexbox-ucpN)
- Live Site URL: [Live Production Deployment](https://social-proof-section1-one.vercel.app/)

## My process

### Built with

- Semantic HTML5 structural markup (`<main>`, `<section>`, `<footer>`)
- CSS custom properties (Variables)
- Flexbox (For star icon alignments and testimonial inner layouts)
- CSS Grid (For asymmetric layout positioning across the dashboard canvas)
- Responsive design via media query breakpoints

### What I learned

During this challenge, I sharpened my skills with asymmetric CSS layouts and responsive structures. I focused heavily on building structural blocks cleanly without relying on hacky, hardcoded absolute margins.

1. **Stair-step Staggering using `align-self`:** By pairing a defined height or layout wrapper with flex/grid alignment properties, I successfully grid-aligned rows and columns into a cascading, diagonal design pathway.

```css
/* Cascading the three star rating card components */
.rating-card:nth-child(1) { align-self: flex-start; }
.rating-card:nth-child(2) { align-self: center; }
.rating-card:nth-child(3) { align-self: flex-end; }

Continued development
In upcoming projects, I intend to approach my design layouts using a strict Mobile-First workflow. Building layouts fluidly from a small mobile viewport upward makes the stylesheet architecture simpler, reduces rules code overriding, and ensures maintainable code.

AI Collaboration
I used AI to help brainstorm layout strategies, audit syntax conventions, and debug configuration errors during deployment.

Tools Used: Gemini (Google AI)

Usage Context: Figuring out semantic element distribution, structuring conditional container heights, fixing media query design shifts, and managing public URL tracking settings inside Vercel.

Outcomes: Highly effective workflow acceleration. It helped me avoid unnecessary CSS rule redundancy and quickly resolve deployment-specific accessibility barriers.

Author
Frontend Mentor - @emanabd1

GitHub - emanabd1