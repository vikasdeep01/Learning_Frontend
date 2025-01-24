Unit 1 : How to select any element to apply any the css properties.

Uniersal Selector:

*{
    apply to all elements in website
}

Selecting the element by name:

  div{

    properties;
  }

Selecting by ID:

    <div id="box">

    </div>


    #box{

    }

Selecting by class:

    <div class="box">

    </div>


    .box{

    }

Seleting Direct Child elements:

 <div class="box">
          <p> i am a para inside a div </p>
    </div>


    div > p{
             properties
    }

Seleting any child elements:

 <div class="box">
          <p> i am a para inside a div </p>
    </div>


    div p{
             properties
    }
