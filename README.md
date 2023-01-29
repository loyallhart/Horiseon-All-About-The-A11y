# Horiseon-All-About-The-A11y

## Description

### What was our motivation?

- Horiseon marketing agency is requesting website updates. We will refactor the code for their current website to include accessibility and logical structure. The websites look should remain the same. 

### Why did we build this project?

- We built this project to help Horiseon add more accessibility to their current website, ensure the code has logical structure, and that all of the links are working properly. 

### What problems does it solve?

- This project solves the problem for screen readers to properly interpret sections, articles, asides, and banner images by adding the appropriate semantic tags and alt text for the images. The banner is using an aria label. We also were able to fix a broken link for the Search Engine Optimization item in the navigation bar. Lastly, we were able to clean up the CSS by consolidating the selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

### What did we learn? 
- We learned how to refactor starter code and include semantic tags that impact accessibility. We also learned how to reorganize starter code in a logical structure.

## User Story

AS Horiseon, a marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engineers

## Acceptance Criteria

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

## Usage

Here is a reference image for how the website should look at the end of this project.

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](Demo/01-html-css-git-homework-demo.png)

**Note**: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. The customer did not want us to add a media query for the viewport on this project. 

## Deployment 

Deployed application can be found at https://loyallhart.github.io/Horiseon-All-About-The-A11y/


