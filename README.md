# HTML & CSS Project Refactoring

This project focuses on improving the structure, accessibility, and maintainability of a web page using semantic HTML elements and external CSS. 
The project also includes additional enhancements for user experience.

## Table of Contents
- [Project Structure](#project-structure)
- [Improvements Made](#improvements-made)
- [HTML Structure](#html-structure)
- [CSS Enhancements](#css-enhancements)
- [How to Run the Project](#how-to-run-the-project)
- [Accessibility and Best Practices](#accessibility-and-best-practices)

## Project Structure

The project is structured as follows:
/project-root
├── index.html         # Main HTML file with improved structure
├── styles.css         # External CSS file with improved styles

### Files:
- `index.html`: Contains the HTML structure of the page.
- `styles.css`: Contains all the external styles using CSS variables for easier maintenance.

## Improvements Made

### HTML Structure

- **Semantic HTML**: 
  - Replaced non-semantic divs and spans with appropriate semantic tags (`<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`, etc.).
  - Improves readability, maintainability, and accessibility (a11y).

### CSS Enhancements

- **External Styles**: 
  - All inline styles have been moved to the `styles.css` file to improve separation of concerns.
  
- **CSS Variables**: 
  - CSS variables (custom properties) have been used to improve maintainability and consistency across the project.
    These variables help easily update styles such as colors, fonts, and spacing globally.
  
- **Color Consistency & Contrast**:
  - Enhanced color consistency throughout the design by applying a common set of color variables.
  - Improved contrast between text and background to meet accessibility standards and ensure readability.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/mennarihan5/webmasters-codeRefactoringTask

```bash
cd project-repo

```bash
open index.html


