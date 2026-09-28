# Semantic HTML5 Personal Portfolio

A single-page personal portfolio built using **only semantic HTML5**. There is no CSS and no inline styling. The page uses the browser's default layout and styles only.

This project was created for a Web Development course assignment.

## Features

- **Header and navigation:** an `<h1>` title and a `<nav>` with an unordered list (`<ul>`) of links to each section on the page.
- **About and skills:** a short biography, a profile photo inside `<figure>` with descriptive `alt` text, and a description list (`<dl>`) of technical skills.
- **Projects:** three separate project modules, each in its own `<article>`, linking to its public GitHub repository.
- **Contact form:** Name, Email and Message (`<textarea>`) fields, each paired with a `<label>` through matching `for` and `id` attributes, plus a submit button.
- **Footer:** copyright notice and a "Back to top" link.

## HTML5 Elements Used

`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<dl>`, `<dt>`, `<dd>`, `<form>`, `<label>`, `<input>`, `<textarea>`, `<button>`, `<footer>`

## Project Structure

```
├── index.html       # The portfolio page
├── images/
│   └── rajan.jpg    # Profile photo
└── README.md
```

## Validation

The page passes the [W3C Nu Html Checker](https://validator.w3.org/nu/) with **no errors or warnings**.

## How to View

1. Clone the repository:
   ```bash
   git clone https://github.com/Rajankfl/webDevMIT.git
   ```
2. Open `index.html` in any web browser.

No build tools, servers or installation are needed.

## Author

**Rajan Kafle**
GitHub: [@Rajankfl](https://github.com/Rajankfl)
