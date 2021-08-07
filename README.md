# Frontend Mentor - Fylo data storage component solution

My solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n)!

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshots
![image](https://user-images.githubusercontent.com/27814917/128601669-7b09b109-6394-4a47-be0c-34b966489011.png)

![fylo-gif2](https://user-images.githubusercontent.com/27814917/128603052-6140cb1c-474e-46a7-98cc-f429ab38571c.gif)

### Links

- Solution URL: [https://github.com/Iwaneq/fylo-data-storage-component-master](https://github.com/Iwaneq/fylo-data-storage-component-master)
- Live Site URL: [https://fylo-iwaneq-page.netlify.app](https://fylo-iwaneq-page.netlify.app)

## My process

So I started by writing a HTML document. Next I wrote some variables in SASS file, and started styling website. When I finished mobile desing, I made it responsive for wider screens. After that I changed a little bit media queries for *main-content class* from precentage widths, to pixel widths. Next I added animations to menu buttons, and finally I linked up my GitHub profile to link on website.

### Built with

To acomplish this challenge I used:
- HTML
- SASS and CSS
- Flexbox
- Mobile-first workflow

### What I learned

I recaped my HTML, CSS and SASS knowledge. By making website responsive I also learned couple of tricks, how to do it better, with much less code. I also repeated topic about animations in CSS, to make buttons animations look more professional and natural.

![fylo-gif1](https://user-images.githubusercontent.com/27814917/128602719-cdae0fb9-f158-4c19-a011-6cff4eec8986.gif)

Some snippets from my code:

```html
<div class="button">
  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="24"><path fill="#697ED4" d="M12.028 0H2.436A2.387 2.387 0 00.049 2.398L.037 21.583a2.387 2.387 0 002.387 2.398h14.4a2.397 2.397 0 002.398-2.398V7.194L12.028 0zM10.83 8.393V1.8l6.595 6.594h-6.595z"/></svg>
  <div class="button__bg"></div>
</div>
```
Buttons!


```scss
body{
    min-height: 100vh;
    background: url("../images/bg-mobile.png") no-repeat center center fixed;
    background-size: cover;
    position: relative;
    color: white;
    font-size: 12px;
    font-family: 'Raleway', sans-serif;
    font-weight: 200;

    @media (min-width:$small-laptop) {
        background: url("../images/bg-desktop.png") no-repeat center bottom fixed;
        background-color: $secondary;
        background-size: 100% 50%;
    }
    @media (min-width:$medium-laptop) {
        font-size: 14px;
    }
}
```
Body and its media queries in SASS

### Continued development

In the future I want to focus on responsive websites and CSS animations.

### Useful resources

- [Produce maintainable CSS with SASS](https://openclassrooms.com/en/courses/5625786-produce-maintainable-css-with-sass) - Free SASS course from Openclassrooms. Everything I know about SASS, I know from here ;p
- [Modern CSS animations](https://openclassrooms.com/en/courses/5625816-create-modern-css-animations) - Free course (another from Openclassrooms) about modern CSS animations. I strongly encourage you to check this out! ;p
- ["HTML and CSS Tutorial for 2021 - COMPLETE Crash Course!" by DesignCourse](https://www.youtube.com/watch?v=D-h8L5hgW-w&t=6946s) - I learned some things about responsive design from that video.

