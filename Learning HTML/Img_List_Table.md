# Images, Lists and Tables in HTML

---

# Images in HTML

Images are displayed using the `<img>` tag.

The `src` attribute specifies the image location, while `alt` provides alternative text if the image cannot be loaded.

## Syntax

```html
<img src="image.jpg" alt="Image Description">
```

---

## Example 1: External Image

```html
<img
    src="https://example.com/image.jpg"
    width="300">
```

### Explanation

* `src` → Image URL
* `width` → Controls image width

---

## Example 2: Local Image

```html
<img
    src="/Learning HTML/Web.png"
    alt="Web"
    width="800">
```

### Explanation

* Local images are stored inside the project folder.
* `alt` provides a text description of the image.

---

# Common Image Attributes

| Attribute | Purpose          |
| --------- | ---------------- |
| src       | Image location   |
| alt       | Alternative text |
| width     | Image width      |
| height    | Image height     |
| title     | Tooltip text     |

---

# Lists in HTML

Lists are used to display related items together.

There are two main types:

1. Unordered Lists
2. Ordered Lists

---

# Unordered List (`ul`)

An unordered list displays items with bullet points.

## Example

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

### Output

* HTML
* CSS
* JavaScript

---

# Ordered List (`ol`)

An ordered list displays items with numbers.

## Example

```html
<ol>
    <li>Learn HTML</li>
    <li>Learn CSS</li>
    <li>Learn JavaScript</li>
</ol>
```

### Output

1. Learn HTML
2. Learn CSS
3. Learn JavaScript

---

# Ordered List with Type Attribute

The `type` attribute changes the numbering style.

## Example

```html
<ol type="A">
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ol>
```

### Output

A. HTML

B. CSS

C. JavaScript

---

# List Tags Summary

| Tag | Purpose        |
| --- | -------------- |
| ul  | Unordered List |
| ol  | Ordered List   |
| li  | List Item      |

---

# Tables in HTML

Tables are used to organize data into rows and columns.

---

# Basic Table Structure

```html
<table border="1">

    <tr>
        <th>Name</th>
        <th>Course</th>
        <th>Age</th>
    </tr>

    <tr>
        <td>Rahul</td>
        <td>B.Tech</td>
        <td>20</td>
    </tr>

</table>
```

---

# Example Table

```html
<table border="1">

    <tr>
        <th>Name</th>
        <th>Course</th>
        <th>Age</th>
    </tr>

    <tr>
        <td>Rahul</td>
        <td>B.Tech</td>
        <td>20</td>
    </tr>

    <tr>
        <td>Priya</td>
        <td>BCA</td>
        <td>19</td>
    </tr>

    <tr>
        <td>Amit</td>
        <td>B.Sc</td>
        <td>21</td>
    </tr>

</table>
```

### Output

| Name  | Course | Age |
| ----- | ------ | --- |
| Rahul | B.Tech | 20  |
| Priya | BCA    | 19  |
| Amit  | B.Sc   | 21  |

---

# Understanding Table Tags

### `<table>`

Creates a table.

### `<tr>`

Creates a table row.

### `<th>`

Creates a heading cell.

Text is usually bold and centered.

### `<td>`

Creates a normal data cell.

---

# Tags Used

| Tag   | Purpose            |
| ----- | ------------------ |
| img   | Display an image   |
| ul    | Unordered list     |
| ol    | Ordered list       |
| li    | List item          |
| table | Create a table     |
| tr    | Table row          |
| th    | Table heading cell |
| td    | Table data cell    |

---

# Quick Revision

## Image

```html
<img src="image.jpg" alt="Image">
```

---

## Unordered List

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
</ul>
```

---

## Ordered List

```html
<ol>
    <li>HTML</li>
    <li>CSS</li>
</ol>
```

---

## Table

```html
<table border="1">

    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>

    <tr>
        <td>Rahul</td>
        <td>20</td>
    </tr>

</table>
```

---

# Key Points

* Use `<img>` to display images.
* Use `<ul>` for bullet lists.
* Use `<ol>` for numbered lists.
* Use `<table>` to organize data into rows and columns.
* Tables consist of rows (`tr`), heading cells (`th`), and data cells (`td`).
