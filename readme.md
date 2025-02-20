# Personal Website Documentation

## Overview
This documentation outlines the structure and components of my personal website, showcasing key sections such as Home, About Me, Projects, and Contact.

## HTML Structure

### `<!DOCTYPE html>`
Declares the document type and HTML version.

### `<html lang="en">`
Defines the language attribute as English.

### `<head>`
Contains metadata and references to external CSS files:
- `<meta charset="UTF-8">` sets the character encoding.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">` sets the viewport settings for responsive design.
- `<title>Personal Website</title>` sets the page title.
- `<link rel="stylesheet" href="CSS/Base/global.css">` links to the global CSS file.
- `<link rel="stylesheet" href="CSS/Layout/layout.css">` links to the layout CSS file.
- `<link rel="stylesheet" href="CSS/Components/forms.css">` links to the forms CSS file.
- `<link rel="stylesheet" href="CSS/Font/font.css">` links to the font CSS file.
- `<link rel="preconnect" href="https://fonts.googleapis.com">` and `<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>` preconnect to Google Fonts.
- `<link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">` links to the Raleway font family from Google Fonts.

### `<body>`
Defines the body of the HTML document containing the main content.

#### `<header>`
Contains the navigation bar:
- `<nav>` and `<ul>` elements organize navigation links.
- `<li>` elements contain `<a>` links to different sections of the page (Home, About Me, Project, Contact).

#### `<main>`
Main content area divided into sections:
- `<div class="container-img">` contains an image with class "mypicture" and alt text "Putu Arya Wibawa".
- `<section id="home">` defines the Home section with a heading, subheading, and a paragraph describing the user and their education.
- `<hr class="divider">` inserts a horizontal rule to separate sections.
- `<section id="aboutme">` defines the About Me section with subsections for Education, Experiences, Skills, and Interests. Each subsection contains an ordered list (`<ol>`) with relevant items (`<li>`).
- `<section id="project">` defines the Project section with a heading and a paragraph describing the user's project.

#### `<footer id="contact">`
Contains the Contact section with a heading and a form:
- The form (`<form>`) uses the POST method and contains labeled input fields for Full Name, E-mail, and Messages.
- A submit button (`<button type="submit">Submit</button>`) sends the form data.

### CSS Files
External CSS files are linked in the `<head>` section to style the website:
- `global.css`: Global styles for the entire website.
- `layout.css`: Layout-specific styles.
- `forms.css`: Styles for form elements.
- `font.css`: Font-related styles.

### Google Fonts
Raleway font family is imported from Google Fonts for use throughout the website.