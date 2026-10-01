# Frontend Mentor - Recipe Page Solution
 
This is my solution to the https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm.
 
The goal was to recreate the provided desktop and mobile designs as closely as possible while practicing semantic HTML, CSS styling, responsive design, and Git/GitHub workflow.
 
## Table of contents
 
- #overview
- #the-challenge
- #screenshot
- #links
- #my-process
- #built-with
- #what-i-learned
- #continued-development
- #author
 
## Overview
 
### The challenge
 
The challenge was to build a responsive recipe page that closely matches the provided Frontend Mentor designs.
 
The page includes:
 
- Recipe image and introduction
- Preparation time section
- Ingredients list
- Step-by-step instructions
- Nutrition table
- Responsive desktop and mobile layouts
 
### Screenshot
<img width="570" height="380" alt="Screenshot 2026-09-30 193621" src="https://github.com/user-attachments/assets/8ff8df4b-ff6e-4c27-86f6-3edbdb2c79e5" />

<img width="557" height="330" alt="Screenshot 2026-09-30 193659" src="https://github.com/user-attachments/assets/fee11150-7ad3-4031-af5b-e0549eee4063" />


### Links
 
- Solution URL: [Add Frontend Mentor solution URL here]
- Live Site URL: https://qcyrus8j562z1111.github.io/recipe-page-main/
 
## My process
 
I started by building the complete HTML structure before writing any CSS. I then improved the markup by separating the recipe into semantic sections for the hero content, preparation time, ingredients, instructions, and nutrition information.
 
Once the HTML structure was finished, I styled the page from top to bottom. I started with the global styles, fonts, colors, and recipe card before moving through each individual section.
 
I used small Git commits throughout the project so that each major stage of the build had its own checkpoint.
 
After completing the desktop layout, I compared it against the provided reference design and adjusted details such as spacing, colors, typography, and border radiuses.
 
Finally, I added a media query for smaller screens and tested the layout at multiple viewport widths using browser developer tools.
 
### Built with
 
- Semantic HTML5
- CSS custom properties
- CSS media queries
- Responsive design
- Google Fonts
- Young Serif
- Outfit
- Git
- GitHub
 
### What I learned
 
This project helped me better understand how to break a design into individual sections before styling it.
 
I also became more comfortable using CSS custom properties to manage colors:
 
```css
:root {
--clr-primary-heading: hsl(14, 45%, 36%);
--clr-primary-accent: hsl(332, 51%, 32%);
--clr-body-text: hsl(30, 10%, 34%);
}
```
 
I practiced using more specific selectors when different headings needed different styles. For example, the main heading uses a dark color while the section headings use the brown accent color.
 
```css
h1 {
color: var(--clr-heading-dark);
}
 
h2 {
color: var(--clr-primary-heading);
}
```
 
Another important part of this project was responsive design. I learned how desktop styles can be overridden with a media query instead of creating separate HTML for mobile devices.
 
I also gained more experience debugging CSS. During the project I caught issues involving selector specificity, font imports, and a mobile image selector that did not match the HTML.
 
One of my biggest takeaways was learning to work incrementally. Building and committing one section at a time made it much easier to understand what each change was doing and to debug problems when they appeared.
 
### Continued development
 
I want to continue improving my ability to recreate designs accurately from reference images, especially:
 
- Responsive layouts
- Spacing and sizing
- CSS organization
- Accessibility
- Semantic HTML
- Using browser developer tools for debugging
- Writing clean Git commit histories
 
I also want to become better at deciding when a design is finished instead of endlessly adjusting small CSS values.
 
## Author
 
- Name: Quentin Cyrus
- GitHub: https://github.com/qcyrus8j562z1111
- Frontend Mentor: [Add your Frontend Mentor username/profile URL]
