# HTML Basics

[Next Page](Img_List_Table.html)

---

# Headings

HTML provides six levels of headings.

```html
<h1>This is Heading 1 (Most Important)</h1>
<h2>This is Heading 2</h2>
<h3>This is Heading 3</h3>
<h4>This is Heading 4</h4>
<h5>This is Heading 5</h5>
<h6>This is Heading 6 (Least Important)</h6>
```

### Output

# This is Heading 1 (Most Important)

## This is Heading 2

### This is Heading 3

#### This is Heading 4

##### This is Heading 5

###### This is Heading 6 (Least Important)

---

# Paragraphs

The `<p>` tag is used to write paragraphs.

A paragraph automatically starts on a new line and adds spacing before and after the content.

### Example

```html
<p>
    HTML provides the paragraph tag to write blocks of text.
    A paragraph automatically starts on a new line and adds
    some spacing before and after the content.
</p>
```

### Output

HTML provides the paragraph tag to write blocks of text. A paragraph automatically starts on a new line and adds some spacing before and after the content.

---

Another paragraph example:

```html
<p>
    This is another paragraph. Multiple paragraphs can be
    used to organize content and improve readability.
</p>
```

### Output

This is another paragraph. Multiple paragraphs can be used to organize content and improve readability.

---

# Links

The `<a>` (anchor) tag is used to create hyperlinks.

Links can connect:

* One webpage to another webpage
* A website to another website
* A file
* An email address
* A section of the same page

---

## External Link

```html
<a href="https://www.google.com">
    Visit Google
</a>
```

Output:

Visit Google

---

## Open Link in New Tab

```html
<a href="https://www.youtube.com" target="_blank">
    Open YouTube in New Tab
</a>
```

### Explanation

* `href` → Destination URL
* `target="_blank"` → Opens link in a new tab

---

## Link with Title Attribute

```html
<a href="https://www.github.com"
   title="Click to visit GitHub">
   Visit GitHub
</a>
```

### Explanation

* `title` shows a tooltip when the user hovers over the link.

---

# Important Points

### Headings

* Used to define the importance of content.
* Help organize webpage structure.
* Useful for SEO and accessibility.

### Paragraphs

* Used to write text content.
* Automatically start on a new line.
* Improve readability.

### Links

* Connect webpages, websites, files, and sections.
* Created using the `<a>` tag.
* Use the `href` attribute to specify the destination.

---

# Tags Covered

| Tag     | Purpose         |
| ------- | --------------- |
| h1 - h6 | Headings        |
| p       | Paragraph       |
| a       | Hyperlink       |
| hr      | Horizontal Line |
| br      | Line Break      |

---

# Quick Revision

```html
<h1>Main Heading</h1>

<p>This is a paragraph.</p>

<a href="https://google.com">
    Google
</a>

<hr>

<br>
```
