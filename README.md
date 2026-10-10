# Personal Portfolio Website

## Student Information

- Name: Ebenezar Uju
- Course: INFR3120 – Web and Scripting Programming
- Assignment: Assignment 1 – Portfolio Website

## Overview

This project is a responsive personal portfolio website created using HTML5 and CSS3. The website contains four separate pages:

- `index.html` – Home page
- `about.html` – About Me page with my photo and introductory video
- `projects.html` – Projects page
- `contact.html` – Contact Me page with a validated form

The website includes semantic HTML, responsive design, CSS gradients, a colour scheme, form validation, and accessibility considerations.

## Responsive Design

The website uses fluid design, percentage widths, `max-width`, and separate CSS files for different screen sizes.

- Mobile: 0px–600px using `mobile.css`
- Tablet: 601px–1024px using `tablet.css`
- Laptop/Desktop: 1025px and wider using `laptop.css`

These viewport sizes were used because mobile devices need a narrow stacked layout, tablets need medium spacing, and laptop/desktop screens allow wider content areas.

No Flexbox was used in this project.

## Gradients

A standard linear gradient is used in the website header:

```css
background: linear-gradient(#16324f, #1f6f8b);
```

An angled linear gradient is used in the Home page hero section:

```css
background: linear-gradient(135deg, #1f6f8b, #99d5c9);
```

The gradients help create a more visually interesting and consistent design.

## Colour Scheme

The website uses the following colour scheme:

- Navy: `#16324F`
- Blue: `#1F6F8B`
- Teal: `#99D5C9`
- Cream: `#F7C59F`
- Red: `#D1495B`

Blue and teal were selected for a professional technology-focused appearance. Cream and red are used for contrast, highlights, and buttons.

## Semantic HTML

The website uses semantic HTML tags to organize content and improve accessibility:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
<form>
<label>
```

## Testing and Validation

The website was tested and validated before submission.

- HTML pages were tested using the W3C Markup Validation Service.
- CSS files were tested using the W3C CSS Validation Service.
- Website links were tested using the W3C Link Checker.
- Spelling was checked and corrected.
- Accessibility was tested using the WAVE Web Accessibility Evaluation Tool.
- The website was tested at mobile, tablet, and laptop/desktop screen widths.
- Navigation links, images, video, contact form validation, and footer email links were tested and are working correctly.

## GitHub and Deployment

This project is stored in a public GitHub repository and deployed using GitHub Pages.

- GitHub Repository: https://github.com/ebenezaruju-cmyk/Portfolio-site
- Live GitHub Pages Website: https://ebenezaruju-cmyk.github.io/Portfolio-site/

The site was deployed from the `main` branch using the root folder.

## External Sources

Course lectures and course examples were used to learn HTML, CSS, semantic tags, media queries, gradients, and form validation.

Any external code or resources used in this project were reviewed, understood, documented, and kept within the assignment requirements.