# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
This is a Replica of a Clipboard Landing Page Challange presented Frontend Mentors Made with Pure HTML5 and Css

### The challenge

My task was to build out the project to the designs that looks close exactly to what was i was given.

Users should be able to:


- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Desktop view](./images/Screenshot_desktop_view.png)
![Mobile View](./images/Screenshot_mobile_view.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop workflow.

### What I learned

I learned a myraid of things during the course of building this project which includes: Completely laying out the structure of the webpage utilizing Semantic Html5 before styling, Using flexbox and Grid to manipulate layout, centering and positioning Elements, Using variables to assign a lot of Css property and as well how to import fonts from Google and lot more.

```html
<h1> <a href="#" class="head_btn_green">Download for iOS</a>
     <a href="#" class="head_btn_blue">Download for Mac</a> </h1>
```
```css
.header .head_btn_green{
    display:inline-block;
    background: var(--strong-cyan);
    color:#fff;
    text-decoration:none;
    margin:20px auto;
    padding:15px 25px;
    border-radius:50px;
    cursor:pointer;
}
.header .head_btn_blue{
    display:inline-block;
    background: var(--light-blue);
    color:#fff;
    margin:20px auto;
    padding:16px 25px;
    border-radius:50px;
    text-decoration:none;
    cursor:pointer;
}
}
```
```css
:root{
    /*primary*/
    --strong-cyan:#26baa4;
    --light-blue:#6173ff;
    
    /*neutral*/
    --dark-greyish-blue:#4c545d;
    --grayish-blue:#e4e4e4;
}
```
```css
.flex{
    display:flex;
    justify-content:center;
    align-items:center;
}

.grid{
    display:grid;
    grid-template-columns:1fr;
    gap:10px;
    -moz-display:grid;
    -moz-grid-template-columns:1fr;
    -moz-gap:10px;
}

}
```

### Continued development

The sole area I'd like to focus more on is that of Css ::before and after psuedo selector.


### Useful resources

- [Frontend Mentors 1](https://www.frontendmentor.io) - This site actually pioneered this challange and really helped me towards ehancing my skills and reducing imposter syndromes. 
- [Freecodecamp 2](https://freecodecamp.org) - This is an amazing website which helped me finally understand the basics of html and css. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@Dike-Code](https://www.frontendmentor.io/profile/Dike-Code)
- Twitter - [@Dike_O_Clinton](https://www.twitter.com/Dike_O_Clinton)


## Acknowledgments
There's a lot of facilitators I would like to acknowlege tremendeously for their essential help towards learning and creating projects and they include:
1. Brad Traversy pioneer of Traversy Media on youtube.
2. freecodecamp and it's officials.
3. W3schools.
4. Dev.Ed
Only but few to mention.

