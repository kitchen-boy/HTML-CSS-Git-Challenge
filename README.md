# HTML-CSS-Git-Challenge
Code Refactor Assignment for Module 1 - Bootcamp

To optimize WebPage for search engines by editing codebase to follow accessibility standards:

This repository contains a code refactoring for Horiseon. 
The purpose of this refactor is to modify the existing codebase so that the code meets accessibility standards and the site is optimized for search engines. 
In addition to modifying the HTML I have also made the CSS more efficient, by consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

* Semantic HTML elements in structure.
* HTML elements follow a logical structure independent of styling and positioning.
* Image elements have accessible alt attributes.
* Heading attributes fall in sequential order.
* Title element has a concise, descriptive title.

The following is a summary of edits to the codebase:

HTML index refactor
* Changed <title> from "website" to "Horiseon", the name of website.
* Added semantic HTML elements: 
  - Changed div to header.
  - Changed div to nav.
  - Changed div to section.
  - Changed div to aside.
* Fixed nav link for "Search Engine Optimization".
* Chose appropriate text alternatives for decorative images and icons:
  - Hid decorative images & icons by adding a null (empty) text alternative (alt="")
  - Cleaned code - removed unnecessary /img.
* 

CSS Refactor
* Added CSS Table of Contents
* Changed div to nav
* Reduced repetitive code:
  - Cleaned up code by adding font color & font-family to "section" content
  - Cleaned up code by adding font color to "aside" benefits
  - Cleaned up code - Removed repetitive h3 attributes
  - Cleaned up code - Removed repetitive img attributes