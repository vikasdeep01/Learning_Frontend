// Lets understand box model 

Every element present on the webpage have 3 peoperties :

padding: some Unit  
// space between the actual content and border

margin: some Unit   
// how much distance it will make with other elments

border: some unit   
// what is the border


if ( box-sizing:border-box;)
{
    total height is : top margin + bottom margin + content height + padding top and bottom + border
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
text-decoration: underline
text-decoration-color:any-colour;
text-decoration-style: dotted;   
line-height: some unit
letter-spacing: some units
text-transform: uppercase,lowercase,capitalize;
text-align: center,

overflow: hidden ,
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




