# HTML Containers: Div, ID, Class and Semantic Tags

These elements help organize content and make webpages easier to style and maintain.

---

# The `<div>` Tag

The `<div>` tag is a generic container used to group HTML elements together.

By itself, it has no visual appearance.

## Syntax

```html
<div>

</div>
```

## Example

```html
<div>
    <h2>About Me</h2>

    <p>
        I am learning Web Development.
    </p>
</div>
```

### Why Use Div?

* Group related content
* Apply CSS styles to multiple elements
* Create page layouts
* Organize code

---

# The `id` Attribute

An `id` uniquely identifies an HTML element.

### Syntax

```html
<tag id="unique-name">
```

## Example

```html
<h1 id="main-heading">
    Welcome
</h1>
```

### Rules

* Must be unique on the page
* One element should have one unique ID
* Used by CSS and JavaScript

### Example

```html
<div id="header">
    Website Header
</div>
```

---

# The `class` Attribute

A class is used to group multiple elements together.

### Syntax

```html
<tag class="class-name">
```

## Example

```html
<p class="info">
    First Paragraph
</p>

<p class="info">
    Second Paragraph
</p>
```

### Why Use Class?

* Apply same styles to multiple elements
* Easier CSS management
* Reusable styling

---

# Difference Between ID and Class

| Feature       | ID          | Class             |
| ------------- | ----------- | ----------------- |
| Unique        | Yes         | No                |
| Can be reused | No          | Yes               |
| CSS Selector  | #id         | .class            |
| Usage         | One element | Multiple elements |

---

## Example

```html
<div id="header">
    Website Header
</div>

<p class="info">
    Paragraph One
</p>

<p class="info">
    Paragraph Two
</p>
```

---

# Why Semantic Tags?

Before HTML5, developers used many divs:

```html
<div id="header">
</div>

<div id="navigation">
</div>

<div id="content">
</div>

<div id="footer">
</div>
```

Problem:

* Hard to understand code
* Poor readability
* Less meaningful structure

HTML5 introduced Semantic Tags.

---

# Semantic Tags

Semantic tags describe the purpose of the content.

Example:

```html
<header>
</header>

<nav>
</nav>

<main>
</main>

<footer>
</footer>
```

Even without reading the content, we understand the page structure.

---

# `<header>`

Represents the top section of a webpage.

Usually contains:

* Logo
* Website title
* Navigation links

## Example

```html
<header>

    <h1>My Website</h1>

</header>
```

---

# `<nav>`

Represents navigation links.

## Example

```html
<nav>

    <a href="#">Home</a>

    <a href="#">About</a>

    <a href="#">Contact</a>

</nav>
```

---

# `<main>`

Represents the main content of the page.

Usually only one main element exists per page.

## Example

```html
<main>

    <h2>Welcome</h2>

    <p>
        Main page content.
    </p>

</main>
```

---

# `<section>`

Represents a logical section of content.

## Example

```html
<section>

    <h2>About Us</h2>

    <p>
        Company information.
    </p>

</section>
```

---

# `<article>`

Represents self-contained content.

Examples:

* Blog post
* News article
* Forum post
* Product review

## Example

```html
<article>

    <h2>HTML Basics</h2>

    <p>
        Learning HTML is fun.
    </p>

</article>
```

---

# `<aside>`

Represents side content.

Examples:

* Advertisements
* Related articles
* Sidebar links

## Example

```html
<aside>

    <h3>Related Posts</h3>

</aside>
```

---

# `<footer>`

Represents the bottom section of a webpage.

Usually contains:

* Copyright
* Contact information
* Social links

## Example

```html
<footer>

    <p>
        Copyright 2026
    </p>

</footer>
```

---

# Complete Semantic Layout Example

```html
<!DOCTYPE html>
<html>

<head>
    <title>Semantic Layout</title>
</head>

<body>

    <header>
        <h1>My Website</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>

    <main>

        <section>

            <h2>About Us</h2>

            <p>
                Welcome to our website.
            </p>

        </section>

        <article>

            <h2>Latest News</h2>

            <p>
                New course launched.
            </p>

        </article>

        <aside>

            <h3>Related Links</h3>

        </aside>

    </main>

    <footer>

        <p>
            Copyright 2026
        </p>

    </footer>

</body>
</html>
```

---

# Visual Structure

```text
+-------------------+
|      HEADER       |
+-------------------+

| Navigation Menu   |

+-------------------+
|                   |
|      MAIN         |
|                   |
|  SECTION          |
|  ARTICLE          |
|  ASIDE            |
|                   |
+-------------------+

|      FOOTER       |
+-------------------+
```

---

# Quick Revision

### Div

```html
<div>

</div>
```

Generic container.

---

### ID

```html
<div id="header">

</div>
```

Unique identifier.

---

### Class

```html
<div class="card">

</div>
```

Reusable grouping.

---

### Semantic Tags

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

Meaningful page structure.

---

# Tags Covered

| Tag     | Purpose             |
| ------- | ------------------- |
| div     | Generic Container   |
| header  | Top Section         |
| nav     | Navigation          |
| main    | Main Content        |
| section | Content Section     |
| article | Independent Content |
| aside   | Sidebar Content     |
| footer  | Bottom Section      |

### Key Rule

**Use semantic tags whenever possible.**

Use `<div>` when no suitable semantic tag exists.
