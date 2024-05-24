<script setup >


</script>
<template>
<header class="head">
  
   <ul class="head" >

   <div class="logo" ><img src="file:///C:/Users/naiti/Downloads/Logo.svg" alt="">    </div>
    
   <div  class="sea"   >
    <i class="searchimage" > <img src="file:///C:/Users/naiti/OneDrive/Desktop/card/Search.svg" alt=""></i>
        <input placeholder="search "   class="Search"   >
   </div>
    
    <li>   
    <nav class="navigation">
            <li>  Home    </li>
            <li>   About us     </li>
                <li>  Contact us    </li>
                    <li>   Blog     </li>
     </nav>
    </li>
     <li> <img src="file:///C:/Users/naiti/Downloads/Icons.svg" alt=""></li>



    

       

                       
   </ul>
   
</header>
</template>



 <style scoped>
  
 
.head{
    display: flex;
flex-direction: row;
justify-content: space-between;
align-items: center;


list-style-type: none;
width:100%;
height: 100px;

/* Main/White */
background: #FFFFFF;
border-bottom: 1px solid #B5B5B5;

/* Inside auto layout */


}
/* Header Top */

/* Auto layout */

/*  */
.Search{
    /* Search Field */

/* Auto layout */
/* Search Field */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: center;
padding: 16px;
gap: 8px;

margin: 0 auto;
width: 372px;
height: 58px;
border: none;
background: #F5F5F5;
background-image: url(":file///C:/Users/naiti/AppData/Local/Temp/6646c194-0d9f-41a5-896d-c9d598f1b0fe_TedX%20task%20-%201%20(2).zip.0fe/Icon/32px/Search.svg");
border-radius: 8px;

/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;



}

.sea{
    display: flex;
    background: #F5F5F5;
    border-radius: 8px;

}

.searchimage{
    
  align-content: center;
  padding-left: 10px ;

}
.navigation{
    /* Navigation */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px;
gap: 52px;

margin: 0 auto;
width: 351px;
height: 19px;


/* Inside auto layout */
flex: none;
order: 2;
flex-grow: 0;
font-family: -apple-system, BlinkMacSystemFont, sans-serif;
                                                 
}

</style>