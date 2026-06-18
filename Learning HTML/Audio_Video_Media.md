# HTML Media Elements

HTML provides special tags to display audio, video, graphics, and external content on a webpage.

---

# Audio Tag

The `<audio>` tag is used to play sound files.

## Syntax

```html
<audio controls>
    <source src="song.mp3" type="audio/mpeg">
</audio>
```

## Example

```html
<audio controls>
    <source src="music.mp3" type="audio/mpeg">
</audio>
```

### Important Attributes

| Attribute | Purpose                   |
| --------- | ------------------------- |
| controls  | Shows play/pause controls |
| autoplay  | Starts automatically      |
| loop      | Repeats audio             |
| muted     | Starts muted              |

---

# Video Tag

The `<video>` tag is used to display videos.

## Syntax

```html
<video width="400" controls>
    <source src="video.mp4" type="video/mp4">
</video>
```

## Example

```html
<video width="500" controls>
    <source src="movie.mp4" type="video/mp4">
</video>
```

### Important Attributes

| Attribute | Purpose                     |
| --------- | --------------------------- |
| controls  | Shows video controls        |
| width     | Video width                 |
| height    | Video height                |
| autoplay  | Plays automatically         |
| loop      | Repeats video               |
| muted     | Starts muted                |
| poster    | Thumbnail image before play |

Example:

```html
<video
    width="500"
    controls
    poster="thumbnail.jpg">

    <source src="movie.mp4" type="video/mp4">

</video>
```

---

# Iframe Tag

The `<iframe>` tag is used to embed another webpage inside the current webpage.

Examples:

* YouTube Videos
* Google Maps
* Other Websites

## Syntax

```html
<iframe src="https://example.com"></iframe>
```

## Example

```html
<iframe
    src="https://www.wikipedia.org"
    width="600"
    height="300">
</iframe>
```

### YouTube Example

```html
<iframe
    width="560"
    height="315"
    src="https://www.youtube.com/embed/VIDEO_ID">
</iframe>
```

---

# SVG Tag

SVG stands for **Scalable Vector Graphics**.

SVG is used to draw graphics directly in HTML.

Advantages:

* Does not lose quality when zoomed
* Very small file size
* Can be styled with CSS
* Can be manipulated with JavaScript

---

## SVG Rectangle

```html
<svg width="200" height="100">

    <rect
        width="200"
        height="100"
        fill="blue">

    </rect>

</svg>
```

---

## SVG Circle

```html
<svg width="200" height="200">

    <circle
        cx="100"
        cy="100"
        r="50"
        fill="red">

    </circle>

</svg>
```

---

## SVG Line

```html
<svg width="200" height="200">

    <line
        x1="0"
        y1="0"
        x2="200"
        y2="200"
        stroke="black"
        stroke-width="3">

    </line>

</svg>
```

---

# Canvas Tag

The `<canvas>` tag provides a drawing area.

Graphics are drawn using JavaScript.

## Example

```html
<canvas
    id="myCanvas"
    width="300"
    height="150">

</canvas>
```

Canvas is commonly used for:

* Games
* Animations
* Charts
* Drawing Applications

---

# Figure and Figcaption

Used to group media with captions.

## Example

```html
<figure>

    <img
        src="mountain.jpg"
        alt="Mountain">

    <figcaption>
        Beautiful Mountain View
    </figcaption>

</figure>
```

---

# Embed Tag

Used to embed external resources.

## Example

```html
<embed
    src="sample.pdf"
    width="500"
    height="400">
```

Used for:

* PDFs
* Multimedia Files
* External Documents

---

# Object Tag

Another way to embed external content.

## Example

```html
<object
    data="sample.pdf"
    width="500"
    height="400">

</object>
```

---

# Summary of Media Tags

| Tag        | Purpose                        |
| ---------- | ------------------------------ |
| audio      | Play audio                     |
| video      | Display videos                 |
| iframe     | Embed webpages/videos/maps     |
| svg        | Draw vector graphics           |
| canvas     | Draw graphics using JavaScript |
| figure     | Group media content            |
| figcaption | Caption for media              |
| embed      | Embed external resources       |
| object     | Embed external content         |

---

# Quick Revision

### Audio

```html
<audio controls>
    <source src="song.mp3">
</audio>
```

### Video

```html
<video controls>
    <source src="video.mp4">
</video>
```

### Iframe

```html
<iframe src="https://example.com"></iframe>
```

### SVG Circle

```html
<svg width="200" height="200">
    <circle
        cx="100"
        cy="100"
        r="50">
    </circle>
</svg>
```

### Canvas

```html
<canvas
    width="300"
    height="150">
</canvas>
```

---

# Tags Covered

* audio
* video
* iframe
* svg
* canvas
* figure
* figcaption
* embed
* object

After these topics, students will have covered most commonly used HTML tags and can comfortably move on to CSS.
