

//ANCHOR - Uniersal Selector:

                    *{
                        apply to all elements in website
                    }

//ANCHOR - Selecting the element by name:

                    div{

                      properties;
                    }

//ANCHOR - Selecting by ID:



                    #box{

                    }

//ANCHOR - Selecting by class:

                  
                    .box{

                    }

//ANCHOR - Seleting Direct Child elements:


                div > p{
                        properties
                }

//ANCHOR - Seleting any child elements:

                    div p{
                            properties
                    }


//NOTE - Advance selectors 



                      .box:first-child{              //NOTE - where .box is first child of parent 

                          property ;
                      }

//ANCHOR - Attribute selector 
                      

                      [box="1"]{


                           properties ;

                      }
//ANCHOR - Selecting Nth child 

                    .box:nth-child ( 1 to ..){

                      properties ;
                    }

//LINK - Inserting content dynamically using css

          .box::before{
            
               content:add content before the element
          }


          .box::after{
  
               content:add content after the element
          }


          input::placeholder{
            properties:
          }