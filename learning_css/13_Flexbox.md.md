//ANCHOR - Flexbox is introduced in css3 to create layouts easily with less effort

//NOTE -   change the display property of parent to flex 

   .parent-box{

       display:flex;

       flex-direction: row, column; 


        //LINK - row: main axis is x-axis ;
        //LINK - column: main axis is y-axis ;

    //SECTION - to move the content along axes 
      justify-content:   (works in main axis)
      align-items:       (works in opposite axis)
      align- content  :   (if there are multiple rows)

                       flex-start	    Aligns items at the start of the flex container (default).
                       flex-end	        Aligns items at the end of the flex container.
                       center	        Centers items in the flex container.
                       space-between	Items are spaced evenly, with no space at the edges.
                       space-around	    Items are spaced evenly, with equal space around each item.
                       space-evenly	    Items have equal space between and around them.
                       start	        Similar to flex-start, but follows writing mode direction.
                       end	            Similar to flex-end, but follows writing mode direction.
                       left	            Aligns items to the left (works if direction: rtl;).
                       right	        Aligns items to the right (works if direction: rtl;).

      flex-wrap : no-wrap, wrap ,  wrap reverse;

      gap-row   :    some units;
      gap-column:    some units;

   }

     .child boxes{

           height:10vh;
           width:10vh;
     }

  //ANCHOR - order property is used to position the elements if there are multiple child

      .child{
        order: whole number ;        position them in ascending order .
        align-self:                 targetting any particular elements
      }