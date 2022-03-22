# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Profile Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](.//src/images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://emilygaj.github.io/frontend-mentor-challenge/](https://emilygaj.github.io/frontend-mentor-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
  - card styles
  - profile photo styles
  - text styles
- revisited Semantic HTML5 markup to fix text styles and add a span or 2
- CSS customizations again
  - flexbox stuff
  - background and background shapes (with Andrew's help)

### What I learned

I learned a lot about flexbox while I was working on this project, especially through the work I did on the bottom of the profile card! I also learned how to insert a horizontal line (sounds easy but changed the whole look). While working on this challenge, I found I was having a really hard time with flexbox due to the small differences between align and justify - items v. content. Once I figured out the differences between these styles, every started to work!

Here is the code for that:

```css
.stats {
  direction: flex;
  flex-flow: column wrap;
  text-align: center;
  column-count: 3;
  column-fill: balance;
  height: 4rem;
  width: fill;
  justify-content: flex-end;
  align-items: center;
}
```

This is the list that that CSS is referencing, and I was proud of my problem solving skills to style the different list items' text differently:

```html
<ul class="stats">
  <li class="numbers">80K</li>
  <li class="descriptor">Followers</li>
  <li class="numbers">803K</li>
  <li class="descriptor">Likes</li>
  <li class="numbers">1.4K</li>
  <li class="descriptor">Photos</li>
</ul>
```

## Author

- Website - [Emily Gajda](http://emilygajda.com)
- Frontend Mentor - [@emilygaj](https://www.frontendmentor.io/profile/emilygaj)

## Acknowledgments

Andrew Sipes, my professor for MEJO 187 at UNC Chapel Hill gave me so much help on this project! His expertise is invaluable. I also asked my mom for some help, and she helped me chill out and work through it when I couldn't figure out exactly what to do!
