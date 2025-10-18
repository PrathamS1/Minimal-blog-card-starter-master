<!-- Please update value in the {}  -->

<h1 align="center">Minimal Blog Card | devChallenges</h1>

<div align="center">
   Solution for a challenge <a href="https://devchallenges.io/challenge/minimal-blog-card" target="_blank">Minimal Blog Card</a> from <a href="http://devchallenges.io" target="_blank">devChallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://prathams1.github.io/Minimal-blog-card-starter-master/">
      Demo
    </a>
    <span> | </span>
    <a href="https://github.com/PrathamS1/Minimal-blog-card-starter-master">
      Solution
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenge/minimal-blog-card">
      Challenge
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Approach](#my-approach)
- [Built with](#built-with)
- [Contact](#author)

<!-- OVERVIEW -->

## Overview

![screenshot](/resources/screenshot.png)

<!--
Introduce your projects by taking a screenshot or a gif. Try to tell visitors a story about your project by answering:

- What have you learned/improved?
- Your wisdom? :)
-->

### My Approach

In building this minimal blog card, I followed a structured approach starting from the HTML foundation and progressing to CSS styling for a clean, responsive design. Here's a breakdown of the steps taken:

1. **HTML Structure Setup**: I began by creating the basic HTML skeleton in `index.html`. This included setting up the document structure with a container div, a card-container for the main content, an image element for the cactus photo, a capsule div for the "Design" tag, a card-content section with title and description, and a card-footer for the author name. I also added meta tags, font preconnects for Google Fonts (Sora), and a favicon link to ensure proper rendering and performance.

2. **Basic Layout and Positioning**: Using inline styles in the HTML head, I centered the card on the page with flexbox on the body element. I positioned the author info at the top using absolute positioning for a subtle credit overlay.

3. **CSS Styling and Design**: In `style.css`, I defined custom properties for fonts and applied styles to create the card's visual appearance. This involved:
   - Setting up the container with border-radius and box-shadow for a modern look.
   - Using flexbox for the card-container to stack elements vertically.
   - Styling the image with full width and rounded corners.
   - Creating the capsule tag with a purple background and white text, using fit-content width and border-radius for a pill shape.
   - Applying typography styles to the title and description with appropriate font weights, sizes, and colors.
   - Adding padding and margins for spacing, and a bottom border to separate the card content from the footer.

4. **Responsive Considerations**: Although the design is primarily fixed-width, I ensured the card scales well on different devices by using relative units like percentages for widths and rem/em for fonts.

5. **Final Touches**: I linked the external stylesheet, added the author credit, and ensured the overall design matches the challenge requirements for a minimal, clean blog card.

This approach allowed me to build a functional and visually appealing component while reinforcing best practices in semantic HTML and CSS layout techniques.

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox


This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges-dashboard) challenge.

## Author

- Website [Pratham Singh](https://itspratham.netlify.app})
- GitHub [@PrathamS1](https://github.com/PrathamS1})
