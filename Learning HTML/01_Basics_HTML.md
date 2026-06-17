# HTML, CSS, and JavaScript - Introduction

## What is a Website?

A website is a collection of web pages displayed in a web browser.

Every modern website is mainly built using three technologies:

| Technology | Role                            |
| ---------- | ------------------------------- |
| HTML       | Structure of the webpage        |
| CSS        | Styling and appearance          |
| JavaScript | Functionality and interactivity |

---

## Real-Life Example: Building a House

* **HTML** → Bricks, walls, doors, rooms (**Structure**)
* **CSS** → Paint, colors, furniture, decoration (**Appearance**)
* **JavaScript** → Electrical system, automatic doors, security system (**Behavior**)

---

# Role of HTML

**HTML (HyperText Markup Language)** defines the structure and content of a webpage.

### Example

```html
<h1>Welcome</h1>
<p>This is my website.</p>
<button>Click Me</button>
```

HTML tells the browser:

* This is a heading
* This is a paragraph
* This is a button

Without HTML, a webpage cannot exist.

---

# Role of CSS

**CSS (Cascading Style Sheets)** controls the appearance of HTML elements.

### Example

```css
h1{
    color: red;
    text-align: center;
}
```

CSS is used for:

* Colors
* Fonts
* Layouts
* Spacing
* Animations
* Responsive Design

Without CSS, websites look plain and boring.

---

# Role of JavaScript

**JavaScript** makes websites interactive.

### Example

```javascript
button.addEventListener("click", () => {
    alert("Button Clicked");
});
```

JavaScript is used for:

* Button clicks
* Form validation
* Image sliders
* Games
* Dynamic content
* API calls
* Single Page Applications (SPA)

Without JavaScript, websites are mostly static.

---

# How HTML, CSS, and JavaScript Work Together

```text
HTML  → Creates Structure

CSS   → Adds Design

JS    → Adds Behavior
```

### Example

#### HTML

```html
<button id="btn">Click Me</button>
```

#### CSS

```css
#btn{
    background-color: blue;
    color: white;
}
```

#### JavaScript

```javascript
document.getElementById("btn")
        .addEventListener("click", () => {
            alert("Hello");
        });
```

### Result

* HTML creates the button
* CSS styles the button
* JavaScript adds click functionality

Together, these three technologies create modern websites and web applications.
