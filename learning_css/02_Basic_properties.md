//ANCHOR -  Lets understand box model 

Every element present on the webpage have 3 peoperties :

padding: some Unit  
// space between the actual content and border

margin: some Unit   
// how much distance it will make with other elments

border: some unit   
// what is the border


if ( box-sizing:border-box;)
{
    total height is : content height + padding top and bottom + border
}


// Basic properties 

background-color: any colour
color: any colour 

height: any unit
width : any unit 


//Using Fonts


font_family : to change the font;
font-style: to change it into italic
font-weight: making bold
font-size:some units
text-decoration: underline
text-decoration-color:any-colour;
text-decoration-style: dotted;   
line-height: some unit
letter-spacing: some units
text-transform: uppercase,lowercase,capitalize;
text-align: center,

text-overflow: clip,elipsis;
 


//  using custom fonts Google Font 

using import statement 
link your google font 


// colours 

  .hex-color {
  background-color: #ff5733; /* Example: Red-orange */
}

/* 2. RGB (Red, Green, Blue) */
.rgb-color {
  background-color: rgb(255, 87, 51); /* Same as #ff5733 */
}

/* 3. RGBA (RGB with Alpha for Transparency) */
.rgba-color {
  background-color: rgba(255, 87, 51, 0.5); /* 50% transparent red-orange */
}

/* 4. HSL (Hue, Saturation, Lightness) */
.hsl-color {
  background-color: hsl(10, 100%, 60%); /* Same as #ff5733 */
}







# 🎨 Tailwind CSS Reference Note

Direct mapping from standard CSS properties to Tailwind utility classes.

---

## 📦 Box Model & Sizing
Tailwind uses a numeric scale where `1 unit = 0.25rem` (4px).



| CSS Property | Tailwind Class | Examples |
| :--- | :--- | :--- |
| **Padding** | `p-{unit}` | `p-4`, `px-6` (left/right), `py-2` (top/bottom) |
| **Margin** | `m-{unit}` | `m-auto`, `my-10`, `-m-2` (negative margin) |
| **Border Width** | `border-{w}` | `border` (1px), `border-2`, `border-t-4` (top only) |
| **Height** | `h-{unit}` | `h-screen`, `h-full`, `h-64`, `h-[200px]` |
| **Width** | `w-{unit}` | `w-full`, `w-1/2`, `w-vw`, `w-min` |
| **Box Sizing** | `box-border` | `box-border` (Default), `box-content` |

> **Note:** Since Tailwind defaults to `box-border`, the `total height = height property`. Padding and borders do not expand the element's defined size.

---

## 🔡 Typography & Fonts

| Feature | Tailwind Class |
| :--- | :--- |
| **Font Family** | `font-sans`, `font-serif`, `font-mono` |
| **Font Style** | `italic`, `not-italic` |
| **Font Weight** | `font-thin`, `font-normal`, `font-bold`, `font-black` |
| **Font Size** | `text-xs`, `text-sm`, `text-base`, `text-xl`, `text-5xl` |
| **Text Decoration** | `underline`, `no-underline`, `line-through` |
| **Decoration Style**| `decoration-dotted`, `decoration-dashed`, `decoration-wavy` |
| **Text Transform** | `uppercase`, `lowercase`, `capitalize` |
| **Text Alignment** | `text-left`, `text-center`, `text-right`, `text-justify` |
| **Line Height** | `leading-none`, `leading-tight`, `leading-loose` |
| **Letter Spacing** | `tracking-tighter`, `tracking-normal`, `tracking-widest` |
| **Text Overflow** | `truncate`, `text-ellipsis`, `text-clip` |

---

## 🌈 Colors & Backgrounds
Tailwind uses a 50–950 color scale.

* **Text Color:** `text-blue-500`
* **Background Color:** `bg-slate-900`
* **Border Color:** `border-gray-200`
* **Opacity (RGBA):** `bg-orange-500/50` (The `/50` sets 50% transparency)
* **Custom Hex:** `bg-[#ff5733]` (Use square brackets for custom values)

---

## 🖋️ Using Custom Fonts (Google Fonts)

1.  **Import:** Keep your `@import` or `<link>` in your main CSS/HTML.
2.  **Config:** Add to `tailwind.config.js`:
    ```javascript
    theme: {
      extend: {
        fontFamily: {
          'custom': ['"Your Google Font"', 'sans-serif'],
        },
      },
    },
    ```
3.  **Apply:** Use the class `font-custom`.

---

## 🚀 Quick Layout Tips
* **Flexbox:** `flex`, `flex-col`, `items-center`, `justify-between`
* **Grid:** `grid`, `grid-cols-3`, `gap-4`
* **States:** `hover:bg-blue-700`, `focus:outline-none`