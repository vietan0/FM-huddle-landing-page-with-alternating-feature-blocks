# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
	-   [The challenge](#the-challenge)
	-   [Screenshot](#screenshot)
	-   [Links](#links)
-   [My process](#my-process)
	-   [Built with](#built-with)
	-   [What I learned](#what-i-learned)
	-   [Continued development](#continued-development)
	-   [Useful resources](#useful-resources)
-   [Author](#author)
-   [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the site depending on their device's screen size
-   See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

-   Solution URL: [Add solution URL here](https://your-solution-url.com)
-   Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Structure

-   Header
	-   Logo
	-   Button
-   Main
	-   3 sections
	-   Hanging block
-   Footer
	-   Logo
	-   Footer links
	-   Attribution & Copyright

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

-   Two ways to scale `<svg>` element:
	- [(Prefered) Control `<svg>` like an `<img>`](https://stackoverflow.com/a/66051530/17673377)
	- [Using viewBox](https://www.youtube.com/watch?v=TBYJ2V1jAlA)

-	Specify `align-items` to make sure flex items don't stretch ([freeCodeCamp](https://www.freecodecamp.org/learn/responsive-web-design/css-flexbox/align-elements-using-the-align-items-property)): 
![](./align-items.jpg)
![](./align-items-normal.jpg)

```css
.flex-container {
	align-items: /* anything but normal/stretch */ ;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

-   [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
-   [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

-   Website - [Add your name here](https://www.your-site.com)
-   Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
-   Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
