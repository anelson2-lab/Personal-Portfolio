# Personal Portfolio Website

## Accessibility Improvements

The following accessibility improvements were made to my portfolio:

- Added skip navigation links to all three pages so users can skip directly to the main content.
- Added descriptive navigation labels using `aria-label="Main navigation"`.
- Used semantic HTML elements such as header, nav, main, section, article, and footer to organize page content.
- Added a contact form with associated labels, a fieldset, a legend, and required fields.
- Added visible keyboard focus indicators for links, buttons, and form fields.
- Added form validation messages to help users identify missing or invalid information.

WAVE testing was completed on all three pages. Each page received zero errors, zero contrast errors, and zero alerts.

## Visual Design and Gestalt Principles

Two Gestalt principles used in my portfolio are:

**1. Proximity:** Related information is grouped together in sections. The project cards are also grouped together to show that they belong to the same category.

**2. Similarity:** The same colors, fonts, borders, and styling are used throughout all three pages to create a consistent design.

## Color Palette

My portfolio uses a consistent blue color palette:

- Dark blue: `#1e3a8a`
- Light blue: `#dbeafe`
- Page background: `#f2f6ff`
- Dark text: `#1f2937`
- White: `#ffffff`

The colors were selected to create a consistent appearance and maintain readable text contrast.

## Contact Form Testing

The contact form was manually tested to check that users can enter information into each field. The required fields and email input use built-in HTML validation. However, submitting the form displays a 405 Not Allowed error because GitHub Pages does not support processing form submissions. The form is currently a demonstration and does not deliver messages.
