//ANCHOR - So most uses units  in the CSS are as follow and we use them on different sceanerios 

Pixel    :  01 px ; 
//REVIEW - It depends on what screen size you are seeing the webpage but mostly used to give minute things like border


//ANCHOR - View Port Responsive units 

margin : 80vw ;  
marin  : 100vh ;

//REVIEW - no matter in what divice you are viewing it will always take 80% of the width and full height of 100%

//ANCHOR - Relative units 

  em --> it is relative to its parent size  
 rem --> it is relative to the root element


Using vmin or vmax   

//NOTE - It really depend that what device you are viewing 

80vmin  : if height < width then 80% of height 

80vmax  : if height < width then 80% of width 

//ANCHOR - Setting of minimum height and width 

min-height: 80vh;  // minimum height will be 80 vm maximumm is unlimited 

//same goes to the max height 


//ANCHOR - Using percentage is relevant when you know the actual behaviour of parent elements


