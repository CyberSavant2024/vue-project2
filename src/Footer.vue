<template>
    <div class="feet">

        <div class="un">
    <div class="cont">

        <div class="logo" ><img src="file:///C:/Users/naiti/Downloads/Logo%20Vector.svg" alt="">    </div>
         <div class="bom">We are a residential interior design firm located in Portland. Our boutique-studio offers more than</div>
    </div>

    <div class="gh">
    <div id="app">
      <nav class="menu">
        <ul class="dropdown-item">
          <li class="dropdown-item">
            <a href="#" class="serv">Services</a>

            <li class="dropdown-item">
            <a href="#">Bonus program</a>
          </li>
          <li class="dropdown-item">
            <a href="#">Find an order</a>
          </li>
          <li class="dropdown-item">
            <a href="#">Gift cards</a>
          </li>
          <li class="dropdown-item">
            <a href="#">Terms of delivery</a>
          </li>
          <li class="dropdown-item">
            Credit and payment
          </li>
          <li class="item dropdown">
           Service contracts

           
            
          </li>
          </li>
        </ul>
        </nav>
        </div>

        <div class="app">

            <nav class="menu">
          <ul class=" dropdown-item">
            <a href="#" class="ass">Assistance to the buyer</a>
            <li class="dropdown-item">
              <li class="dropdown-item">
                <a href="#">Guarantee</a>
              </li>
              <li class="dropdown-item">
                <a href="#">Non-cash account</a>
              </li>
              <li class="dropdown-item">
                <a href="#">Frequently asked questions</a>
              </li>
              <li class="dropdown-item">
                <a href="#">Payment</a>
              </li>
              <li class="dropdown-item">
                <a href="#">Terms of use of the site</a>
              </li>
            </li>
            </ul>

         
         
       
      </nav>
    </div>

</div>


</div>
<div class="social"><img src="file:///C:/Users/naiti/Downloads/Social%20Icons.png" alt=""></div>
</div>
  </template>
  
  <style scoped>
  .menu {
    font-size: large;
    font-family: -apple-system, BlinkMacSystemFont, sans-serif;
    background-color: #000000;
    color: #fff;
    display: flex;
    justify-content: space-between;
    ;
    padding: 10px 20px;
    height: 80%;
   
  }
  
  .menu-list {
    margin: 0;
    padding: 0;
    list-style: none;
    display: flex;
    list-style-type: none;
  }
  
  .menu-item {
    margin: 0 10px;
    
  }
  
  .menu-item a {
    text-decoration: none;
    color: #fff;
  }
  
  .menu-item a:hover {
    color: #ddd;
  }
  
  .dropdown {
    position: relative;
  }
  
  .dropdown-menu {
    background-color: #333;
    color: #fff;
    position: absolute;
    top: 100%;
    left: 0;
    display: none;
    list-style: none;
    padding: 10px;
    height: 100%;
  }
  
  .dropdown:hover .dropdown-menu {
    display: block;
  }
  
  .dropdown-item {
    margin: 5px 0;
    height: 30%;
    list-style-type:none;
    font-family:  -apple-system, BlinkMacSystemFont, sans-serif;;
  }
  
  .dropdown-item a {
    text-decoration: none;
    color: #fff;
  }
  
  .dropdown-item a:hover {
    color: #ddd;
  }
  .gh{
    display: flex;
    margin-left: 30%;
  }
  .feet{
/* Footer */

/* Auto layout */
display: flex;
flex-direction: column;
justify-content: center;
align-items: flex-start;
padding: 104px 160px;
gap: 24px;

width: 100%;
height: 504px;

/* Main/Black */
background: #000000;

/* Inside auto layout */
flex: none;
order: 8;
align-self: stretch;
flex-grow: 0;

  }

.un{
    width: 80%;
    display: flex;
    height: 80%;
}
.bom{
    /* We are a residential interior design firm located in Portland. Our boutique-studio offers more than */

width: 384px;
height: 48px;

font-family: -apple-system, BlinkMacSystemFont, sans-serif;;
font-style: normal;
font-weight: 500;
font-size: large;
line-height: 170.5%;
/* or 24px */

color: #CFCFCF;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;

}
.ass{
  list-style-type: none;
}

  </style>
  