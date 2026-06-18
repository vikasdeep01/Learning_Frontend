# HTML Forms and Input Tags

## What is a Form?

A form is used to collect information from users.

Examples:

* Login Form
* Registration Form
* Contact Form
* Feedback Form
* Survey Form

---

# The `<form>` Tag

The `<form>` tag acts as a container for all form elements.

## Syntax

```html
<form>

</form>
```

## Example

```html
<form>
    <input type="text">
    <button>Submit</button>
</form>
```

---

# Form Attributes

| Attribute    | Purpose                          |
| ------------ | -------------------------------- |
| action       | Where form data will be sent     |
| method       | How data will be sent (GET/POST) |
| autocomplete | Enables or disables suggestions  |

## Example

```html
<form action="/submit" method="post">

</form>
```

---

# The `<input>` Tag

The `<input>` tag is used to create input fields.

## Syntax

```html
<input type="text">
```

The behavior of an input field depends on the value of the `type` attribute.

---

# Text Input

Used to enter text.

```html
<input type="text">
```

Example:

```html
<label>Name:</label>
<input type="text" placeholder="Enter your name">
```

---

# Password Input

Used to enter passwords.

```html
<input type="password">
```

Example:

```html
<label>Password:</label>
<input type="password" placeholder="Enter password">
```

---

# Email Input

Used to enter email addresses.

```html
<input type="email">
```

Example:

```html
<label>Email:</label>
<input type="email" placeholder="Enter email">
```

---

# Number Input

Used to enter numbers.

```html
<input type="number">
```

Example:

```html
<label>Age:</label>
<input type="number" min="1" max="100">
```

---

# Date Input

Used to select a date.

```html
<input type="date">
```

Example:

```html
<label>Date of Birth:</label>
<input type="date">
```

---

# Radio Buttons

Used when only one option can be selected.

```html
<input type="radio" name="gender"> Male
<input type="radio" name="gender"> Female
```

### Important

Radio buttons must have the same `name` value to work as a group.

---

# Checkboxes

Used when multiple options can be selected.

```html
<input type="checkbox"> HTML
<input type="checkbox"> CSS
<input type="checkbox"> JavaScript
```

---

# File Upload

Used to upload files.

```html
<input type="file">
```

---

# Color Picker

Used to select colors.

```html
<input type="color">
```

---

# Range Slider

Used to select a value within a range.

```html
<input type="range" min="0" max="100">
```

---

# Submit Button

Used to submit a form.

```html
<input type="submit">
```

or

```html
<button type="submit">
    Submit
</button>
```

---

# Reset Button

Used to clear all form fields.

```html
<input type="reset">
```

---

# Textarea

Used for multi-line text input.

```html
<textarea></textarea>
```

Example:

```html
<label>Feedback</label>

<textarea rows="5" cols="30">

</textarea>
```

---

# Dropdown Menu

Used to select one option from multiple choices.

```html
<select>
    <option>India</option>
    <option>USA</option>
    <option>Canada</option>
</select>
```

---

# The `<label>` Tag

Labels describe form fields.

Example:

```html
<label>Email</label>
<input type="email">
```

Better Example:

```html
<label for="email">Email</label>

<input
    type="email"
    id="email">
```

Benefits:

* Improves accessibility
* Clicking the label focuses the input

---

# Common Input Attributes

| Attribute   | Purpose                         |
| ----------- | ------------------------------- |
| type        | Type of input                   |
| name        | Name of field                   |
| value       | Default value                   |
| placeholder | Hint text                       |
| required    | Makes field mandatory           |
| readonly    | Prevents editing                |
| disabled    | Disables input                  |
| minlength   | Minimum characters              |
| maxlength   | Maximum characters              |
| min         | Minimum value                   |
| max         | Maximum value                   |
| checked     | Default selected radio/checkbox |

---

# Complete Registration Form Example

```html
<form>

    <label>Name</label>
    <input type="text" placeholder="Enter Name">

    <br><br>

    <label>Email</label>
    <input type="email" placeholder="Enter Email">

    <br><br>

    <label>Password</label>
    <input type="password">

    <br><br>

    <p>Gender</p>

    <input type="radio" name="gender"> Male
    <input type="radio" name="gender"> Female

    <br><br>

    <p>Skills</p>

    <input type="checkbox"> HTML
    <input type="checkbox"> CSS
    <input type="checkbox"> JavaScript

    <br><br>

    <label>Country</label>

    <select>
        <option>India</option>
        <option>USA</option>
        <option>Canada</option>
    </select>

    <br><br>

    <label>Feedback</label>

    <br>

    <textarea rows="5" cols="30"></textarea>

    <br><br>

    <button type="submit">
        Register
    </button>

</form>
```

---

# Tags Covered

| Tag      | Purpose          |
| -------- | ---------------- |
| form     | Form Container   |
| input    | Input Field      |
| label    | Label for Input  |
| textarea | Multi-line Input |
| select   | Dropdown         |
| option   | Dropdown Item    |
| button   | Button           |

---

# Quick Revision

### Form

```html
<form>

</form>
```

### Text Input

```html
<input type="text">
```

### Password

```html
<input type="password">
```

### Radio Button

```html
<input type="radio">
```

### Checkbox

```html
<input type="checkbox">
```

### Dropdown

```html
<select>
    <option>India</option>
</select>
```

### Textarea

```html
<textarea></textarea>
```

### Submit Button

```html
<button type="submit">
    Submit
</button>
```
