# Semantic HTML5 Personal Portfolio

## Project Overview

This project is a single-page personal portfolio website created using **strictly semantic HTML5**. The purpose of the project is to demonstrate how a complete portfolio webpage can be structured without using CSS, JavaScript, or external frameworks.

The webpage relies entirely on the browser's default HTML layout and contains semantic elements such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.

## Features

The portfolio includes the following sections:

* **Header:** Contains the main portfolio title using an `<h1>` element.
* **Navigation:** Contains an unordered list `<ul>` with internal links to different sections of the page.
* **About:** Provides a brief biography and a local profile image.
* **Skills:** Uses a descriptive list `<dl>` to display technical skills and their descriptions.
* **Projects:** Contains at least two independent projects using `<article>` elements.
* **Repository Links:** Each project includes an active repository link.
* **Contact Form:** Includes Name, Email, Message, and Submit fields.
* **Footer:** Contains closing information about the portfolio.

## Technologies Used

* HTML5
* Semantic HTML elements
* Browser-default layout
* Local image assets

No CSS or JavaScript is used in this project.

## Project Structure

```text
portfolio/
│
├── index.html
├── README.md
│
└── images/
    └── profile.jpg
```

## Semantic HTML Structure

The portfolio uses semantic HTML elements to provide a clear document structure.

### `<header>`

Contains the primary title of the portfolio and introductory content.

### `<nav>`

Provides internal navigation links that allow users to move between sections of the single-page website.

### `<main>`

Contains the primary content of the portfolio.

### `<section>`

Separates the major areas of the webpage, including About, Skills, Projects, and Contact.

### `<article>`

Each project is placed inside an independent `<article>` element because each project represents a separate piece of content.

### `<footer>`

Contains the closing information of the portfolio.

## Accessibility

The project uses accessibility-focused HTML practices. The profile image includes meaningful `alt` text, and form fields have explicitly associated `<label>` elements.

For example:

```html
<label for="name">Name:</label>
<input type="text" id="name" name="name">
```

The `for` attribute of the label matches the `id` of the corresponding input, creating an explicit relationship between the label and form control.

## Profile Image

The profile image is stored locally inside the `images` directory.

Example:

```text
images/profile.jpg
```

The image is referenced from `index.html` using:

```html
<img src="images/profile.jpg" alt="Profile photograph">
```

## Projects

The portfolio contains at least two projects. Each project is presented as an independent article and includes a description and an active repository link.

Example projects:

1. **Dining Philosophers Simulation in C**

   * Demonstrates threads, mutexes, semaphores, and synchronization.
   * Includes a link to the project's source-code repository.

2. **Student Management Database**

   * Demonstrates database design and SQL.
   * Includes a link to the project's source-code repository.

## Contact Form

The contact section contains:

* Name input
* Email input
* Message textarea
* Submit button

All fields are explicitly paired with labels to improve accessibility.

## Validation

The completed `index.html` file should be tested using the **W3C HTML Validator**.

Validation is performed to ensure that the HTML document does not contain syntax or markup errors.

The required project submission should include a screenshot showing that the HTML document successfully passes the W3C validation with no errors.

## Design Restrictions

This project intentionally follows these restrictions:

* No CSS
* No inline styling
* No JavaScript
* No external frameworks
* No unnecessary `<div>` elements for the main page structure
* Browser-default HTML layout only

## How to Run

1. Download or clone the project.
2. Make sure `index.html` and the `images` directory are in the correct locations.
3. Open `index.html` in any modern web browser.
4. Use the navigation links to move between the different sections.

## Validation

To validate the webpage:

1. Open the W3C Markup Validation Service.
2. Select the option to validate a file.
3. Upload `index.html`.
4. Run the validation.
5. Correct any reported errors.
6. Repeat the validation until the document passes without errors.
7. Take a screenshot of the successful validation result.

## Author

**Asmit Kumar**

Personal Portfolio – Semantic HTML5 Project
